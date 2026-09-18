---
title: "Waypoint Type"
sidebar_position: 19
---

![](/img/en-img/SharedSets/PointType/0.png)

This setting applies only to waypoint missions. It configures the global waypoint type. Supported waypoint types vary across aircraft models. Different waypoint types result in different flight paths during mission execution. Missions with stop-at-waypoint consume more power since the aircraft must brake to a halt, while non-stop missions are more power-efficient.

### 1. Coordinated Turn
![](/img/en-img/SharedSets/PointType/1.png)

The aircraft does not pass through the waypoint; it turns in advance.

### 2. Straight Flight
![](/img/en-img/SharedSets/PointType/2.png)

The aircraft flies along a straight line.

### 3. Smooth Pass Through Waypoint
![](/img/en-img/SharedSets/PointType/3.png)

The aircraft passes through the waypoint but not via a straight path. It begins turning at a distance before reaching the waypoint.

### 4. Curved Flight
![](/img/en-img/SharedSets/PointType/4.png)

The aircraft flies along Bézier curves.

:::warning
**When using Curved Flight with large elevation differences between waypoints, flight segments may bend downward and cause altitude drops. This behavior may lead to flight safety incidents. Carefully inspect all flight segments during mission planning.**

![](/img/en-img/SharedSets/PointType/5.png)

(Altitude drop between segments in Curved Flight)
:::