---
title: "L/R Extension Distance"
sidebar_position: 25
---

Corridor Wayline allows you to set the outward extension distance of the survey area relative to the centerline.

![](/img/en-img/SharedSets/LRExtend/5.png)

### Flip AOI

For corridor missions, click the ![](/img/en-img/SharedSets/LRExtend/3.png) button to flip the centerline and swap left and right directions.

### Planning Modes

**Bow-shaped wayline**: The flight path is a zigzag route parallel or perpendicular to the centerline. It may fall back to a single flight line if the survey area is too small. The left and right extension distances do not have to be identical; they are synchronized by default. When you modify either the left or right value, the other updates automatically.

![](/img/en-img/SharedSets/LRExtend/0.png)

**Single wayline**: The flight path is a single route following the centerline. **Left and right extension distances must be equal and cannot be excessively large. If set too large, the gimbal FOV may fail to cover the survey area, and the software will trigger a warning.**

![](/img/en-img/SharedSets/LRExtend/4.png)

### Extension Distance Sync

Click the ![](/img/en-img/SharedSets/LRExtend/2.png) button to disable synchronization of left and right extension distances, enabling separate distance values for the left and right sides.

### Cut Distance

When using **Bow-shaped planning** with flight direction set to **Parallel to Centerline**, you can configure the cut distance. When generating flight paths, the software divides the centerline into segments. This ensures the aircraft’s flight distance within each segment does not exceed the defined value and helps prevent signal loss within a single segment.