---
title: "Flight Simulation"
sidebar_position: 5
---

MipMapLink supports flight simulation. When flight simulation is available, a simulation icon ![](/img/en-img/WaylineManager/FlightSimulation/0.png) appears in the upper-right corner of the wayline list / wayline editing page. Click this button to enter flight simulation.

### 1. Simulation controls
Flight simulation supports custom playback speed, custom simulation time, quick jump to previous waypoint and next waypoint.

![](/img/en-img/WaylineManager/FlightSimulation/0.gif)

The dashboard included with flight simulation displays the virtual aircraft flight speed, gimbal pitch, gimbal roll, gimbal yaw, UAV yaw, AGL (above ground level) / ASL / ALT (relative takeoff altitude).

:::warning
Flight simulation is for reference only and cannot reflect complex real-world conditions. Please follow actual field operation conditions.
:::

### 2. Minimap
Flight simulation comes with a minimap. It shows the virtual camera view by default. You can preview virtual footage from each camera, or switch the virtual camera view to the main map.

![](/img/en-img/WaylineManager/FlightSimulation/1.gif)

### 3. Video recording
When the main map displays the virtual camera view, click the recording button on the right. The system captures footage from the virtual camera view and generates SRT subtitle files synchronously. The recorded video can be imported into MipMap Desktop for reconstruction quality testing.
Do not minimize the software during video recording; otherwise, the video frame rate may drop significantly.

![](/img/en-img/WaylineManager/FlightSimulation/1.png)