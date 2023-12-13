# TouchX-Teleoperation-Matlab-ROS
This repository provides tools to integrate Haptic Touch X as a master device for teleoperating simulated or real robots. It includes functionality to map environmental forces to the user's hand for enhanced haptic feedback.
![tele_touchx](https://github.com/aaflakiyan/TouchX-Teleoperation-Matlab-ROS/assets/48828461/39e39321-8cde-43c1-a897-eb0e2aeb711d)

## Installation
In your catkin workspace:
```
git clone https://github.com/bharatm11/Geomagic_Touch_ROS_Drivers.git
```
Adapt the ROS package for your desired robot by cloning it and incorporating the Cartesian velocity controller. Customize the ROS topics in alignment with your specific robot's topics.


## Additional Note
- The Slave blocks included in this context are intended for testing purposes specifically with the Kuka LBR robot, equipped with a Force/Torque sensor.
- To leverage the Force mapping feature, it is essential to obtain End-Effector force data either directly from the robot or through a dedicated Force/Torque sensor.
- You might need to generate custom messages from the ros repository of the Haptic device.

