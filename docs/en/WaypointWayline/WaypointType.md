---
title: "Waypoint Type"
sidebar_position: 21
---

![](/img/en-img/WaypointWayline/WaypointType/0.png)

This setting applies only to wayWaypoint missions. It configures the global wayWaypoint type. Supported wayWaypoint types vary across aircraft models. Different wayWaypoint types result in different flight paths during mission execution. Missions with stop-at-wayWaypoint consume more power since the aircraft must brake to a halt, while non-stop missions are more power-efficient.

### 1. Coordinated Turn
![](/img/en-img/WaypointWayline/WaypointType/1.png)

The aircraft does not pass through the wayWaypoint; it turns in advance.

### 2. Straight Flight
![](/img/en-img/WaypointWayline/WaypointType/2.png)

The aircraft flies along a straight line.

### 3. Smooth Pass Through WayWaypoint
![](/img/en-img/WaypointWayline/WaypointType/3.png)

The aircraft passes through the wayWaypoint but not via a straight path. It begins turning at a distance before reaching the wayWaypoint.

### 4. Curved Flight
![](/img/en-img/WaypointWayline/WaypointType/4.png)

The aircraft flies along Bézier curves.

:::warning
**When using Curved Flight with large elevation differences between wayWaypoints, flight segments may bend downward and cause altitude drops. This behavior may lead to flight safety incidents. Carefully inspect all flight segments during mission planning.**

![](/img/en-img/WaypointWayline/WaypointType/5.png)

(Altitude drop between segments in Curved Flight)
:::