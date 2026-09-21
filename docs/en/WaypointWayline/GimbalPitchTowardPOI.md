---
title: "Gimbal Pitch Toward POI"
sidebar_position: 16
---
When the waypoint yaw mode is set to Toward POI, the waypoint gimbal pitch angle can be configured to face the yaw POI. When the drone flies away from the waypoint after completing the action, both the nose direction and gimbal pitch angle will attempt to point toward the POI. The nose will rotate smoothly to the initial nose direction and gimbal pitch angle of the next waypoint.

If the nose direction and gimbal pitch angle of the next waypoint are also set to target the same POI, the drone’s nose direction and gimbal pitch angle will rotate smoothly throughout the flight segment from the current waypoint to the next waypoint, continuously attempting to face the POI.

>Note
The drone does not natively support the function of pitch angle targeting a POI, so it is not guaranteed that the pitch angle will always point accurately toward the POI.
Implementation principle: Calculate pitch angle A at Waypoint A and pitch angle B at Waypoint B, then perform a smooth rotation from pitch angle A to pitch angle B.

![](/img/en-img/WaypointWayline/GimbalPitchTowardPOI/image-2.gif)

:::tip
**If an action is currently selected, the drone preview prioritizes displaying the state when executing this action. If no action is selected, it shows the state when the drone departs from the waypoint.**
:::