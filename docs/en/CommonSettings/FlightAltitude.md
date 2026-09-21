---
title: "Flight Altitude"
sidebar_position: 6
---

![](/img/en-img/CommonSettings/FlightAltitude/0.png)

:::warning
For consumer-grade UAVs, regardless of the altitude mode selected, the software will automatically convert it to **relative takeoff altitude**.

Therefore, the positional accuracy of the takeoff point is critical for consumer-grade UAVs.

For industrial-grade UAVs, no automatic conversion will be performed.
:::

### 1. ASL
Select this mode when there are strict requirements for flight altitude. You set the absolute altitude of the aircraft, and the flight elevation remains fixed.

### 2. ALT
For example, if the ellipsoidal height of the ground at the aircraft takeoff point is 200 m, and the relative takeoff altitude is set to 100 m, the operating flight altitude of the aircraft will be 300 m (200+100), with a fixed ellipsoidal height.

### 3. AGL
In the above-ground-level mode, the aircraft maintains a constant distance from the ground at all waypoints. The flight altitude is not fixed and will fluctuate following terrain undulations.

For example, if the relative terrain height is set to 100 m:
- At waypoint A where the ground elevation is 20 m, the aircraft flies at 120 m (100+20).
- At waypoint B where the ground elevation is 60 m, the aircraft flies at 160 m (100+60).

#### a. Terrain Reference
![](/img/en-img/CommonSettings/FlightAltitude/1.png)

If the mission type is not a waypoint mission, terrain reference must be configured.

Terrain reference defines which terrain dataset is used as the baseline for automatic terrain-following mission planning. Currently only imported terrain data is supported; the built-in global terrain dataset is not available.

As shown above, after importing terrain data and drawing a survey area on it, select the imported terrain as the terrain reference.

For terrain import instructions, see: [Add Layers](../LayerManager/LayerManager#_6-add-layer)