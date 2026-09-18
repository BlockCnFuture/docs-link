---
title: "Global Transition Speed"
sidebar_position: 11
---

![](/img/en-img/SharedSets/GlobalTransitionSpeed/0.png)

For waypoint missions, this setting defines the aircraft speed from takeoff to the first waypoint, i.e., takeoff speed.

If the mission type is not a waypoint mission, this setting also represents the transition speed between sub-missions. For example, in a nadir plus four-oblique mission, this speed will be used when flying toward the first oblique sub-mission after the nadir sub-mission is completed.

Since no data acquisition is performed in transition segments, the transition speed is only limited by the aircraft’s maximum speed, and is not constrained by GSD or overlap. The aircraft can fly fast in transition zones.

:::tip
Consumer drones do not support takeoff speed configuration. For consumer drones, this setting only controls the flight speed in transition zones.
:::