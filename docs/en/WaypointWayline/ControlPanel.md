---
title: "Control Panel"
sidebar_position: 2
---
![](/img/en-img/WaypointWayline/ControlPanel/image-0.png)

### 1. Left Flight Control Joystick
Hold and drag the joystick with the left mouse button to control the virtual aircraft to translate forward, backward, left and right.
Hold down the W key to move the virtual aircraft forward; hold down the S key to move it backward.
Hold down the A key to translate the virtual aircraft left; hold down the D key to translate it right.

### 2. Right Flight Control Joystick
Hold and drag the joystick with the left mouse button to control the virtual aircraft to ascend, descend, rotate left and rotate right.
Hold down the Q key to rotate the virtual aircraft left; hold down the E key to rotate it right.
Hold down the C key to make the virtual aircraft ascend; hold down the Z key to make it descend.

![](/img/en-img/WaypointWayline/ControlPanel/image-0.gif)

### 3. Waypoint Speed
When the virtual aircraft is locked, this field displays the waypoint speed ![](/img/en-img/WaypointWayline/ControlPanel/image-1.png).

If the virtual aircraft is unlocked, this field displays the virtual flight speed ![](/img/en-img/WaypointWayline/ControlPanel/image-2.png).

### 4. Gimbal Pitch Angle
![](/img/en-img/WaypointWayline/ControlPanel/image-3.png) shows the current gimbal pitch angle of the virtual aircraft.

![](/img/en-img/WaypointWayline/ControlPanel/image-4.png)

Where:

(1) ![](/img/en-img/WaypointWayline/ControlPanel/image-5.png) indicates the current gimbal pitch angle

(2) Indicates the maximum available pitch angle position of the aircraft

(3) Indicates the 30° pitch angle position

(4) Indicates the 0° pitch angle position

(5) Indicates the -45° pitch angle position

(6) Indicates the minimum available pitch angle position of the aircraft

### 5. Aircraft Yaw Angle
![](/img/en-img/WaypointWayline/ControlPanel/image-21.png) shows the current yaw angle of the virtual aircraft.
![](/img/en-img/WaypointWayline/ControlPanel/image-22.png) shows the current gimbal yaw angle of the virtual aircraft, which is generally consistent with the aircraft yaw angle.

### 6. Gimbal Roll Angle
![](/img/en-img/WaypointWayline/ControlPanel/image-23.png)

Shows the current gimbal roll angle of the virtual aircraft. Normally it is 0. Blue indicates the sky and green indicates the ground.

### 7. Gimbal-Heading Lock Status
For some models, the gimbal can be unlocked from the aircraft heading with independent yaw angle configuration. This indicator shows the lock status.

When locked ![](/img/en-img/WaypointWayline/ControlPanel/image-6.png), the gimbal yaw angle of the virtual aircraft synchronizes with the aircraft heading.

In free mode ![](/img/en-img/WaypointWayline/ControlPanel/image-7.png), the gimbal will not automatically synchronize with the aircraft heading.

![](/img/en-img/WaypointWayline/ControlPanel/image-8.png)

### 8. Height Follows Global Settings
This indicator shows whether the virtual aircraft height follows global settings.

![](/img/en-img/WaypointWayline/ControlPanel/image-9.png) When following global settings, the aircraft elevation matches global settings, and the elevation of waypoints added via Space / actions also matches global settings.

![](/img/en-img/WaypointWayline/ControlPanel/image-10.png) When not following global settings, waypoints added via Space / actions adopt the elevation of the virtual aircraft and will not match the global elevation setting.

### 9. Height Relative to Takeoff Point

![](/img/en-img/WaypointWayline/ControlPanel/image-24.png) indicates the height of the virtual aircraft relative to the takeoff point. If no reference takeoff point is set, the elevation of the reference takeoff point is treated as 0.

### 10. Absolute Altitude

![](/img/en-img/WaypointWayline/ControlPanel/image-24.png) indicates the absolute altitude of the virtual aircraft (EGM96).

### 11. Height Above Ground Level

![](/img/en-img/WaypointWayline/ControlPanel/image-25.png) indicates the height of the virtual aircraft relative to terrain.

#### Altitude Indicator
![](/img/en-img/WaypointWayline/ControlPanel/image-12.png)

The altitude indicator shows whether the current flight height is safe. An orange alert triggers when the height above terrain is less than 35 meters ![](/img/en-img/WaypointWayline/ControlPanel/image-18.png); a red alert triggers below 15 meters ![](/img/en-img/WaypointWayline/ControlPanel/image-19.png); a critical warning triggers below 3 meters ![](/img/en-img/WaypointWayline/ControlPanel/image-20.png).

:::warning
**The altitude indicator uses terrain data within the scene for safety reminders. Other models are not considered. The data may not be accurate. Always refer to the actual flight scenario.**
:::

### Gimbal Yaw Angle Dial
![](/img/en-img/WaypointWayline/ControlPanel/image-16.png)

The left and right lines represent the gimbal yaw limit angles for the current model. ![](/img/en-img/WaypointWayline/ControlPanel/image-17.png) represents the gimbal yaw position relative to aircraft heading.

If the aircraft model supports unlocked gimbal from heading, in free mode, a warning will pop up when the difference between gimbal yaw and aircraft heading exceeds the limit angle. If you add related actions under this condition, the exported wayline cannot execute properly.

![](/img/en-img/WaypointWayline/ControlPanel/image-3.gif)


### Third-Person Game Control Mode
Press the V key in the scene to enter or exit third-person game control mode. The mouse cursor is hidden in this mode. Move the mouse left/right to rotate the virtual aircraft left/right; move the mouse up/down to raise/lower the gimbal pitch angle.

![](/img/en-img/WaypointWayline/ControlPanel/image-1.gif)