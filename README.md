Forked Repository of the um7 ROS driver

### Change Log
- Fixed NED and ENU frame conventions.
- Changed standard deviation parameters to covariance array parameters.

### Known problems
- No default vectors for covariance parameters, these have to be available from the parameter server.

ros-drivers-um7
===============

ROS driver for the CH Robotics UM7 inertial measurement device.
Supports standard data and mag topics as well as providing temperature and rpy outputs.
  See the ROS wiki for details:  http://wiki.ros.org/um7
