---
title: "Target Plane Height"
sidebar_position: 13
---

![](/img/en-img/SharedSets/GlobalShootHeight/0.png)

For ground survey flight missions without terrain follow enabled, a target plane must be set. The altitude of the target plane defaults to the altitude relative to the takeoff point that was first defined when creating the mission.

Why is the target plane required? When terrain follow is disabled, the captured target (ground surface) is treated as a flat plane. Since the ground has undulations, the elevation of the target plane needs to be specified.

Once the target plane is confirmed, the GSD can be determined, and the flight planning scheme can be finalized.



The survey area is displayed as a semi-transparent blue overlay on the map, while the target plane appears as a semi-transparent pale yellow plane.

:::warning
Selection of the target plane is critical. For sites with large elevation differences, it is recommended to set the target plane elevation to the maximum terrain height within the survey area.

If the target plane is set to the base of the mountain in such scenarios, insufficient overlap at mountain peaks will likely cause reconstruction failures or holes in the model.
:::