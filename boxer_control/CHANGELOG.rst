^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package boxer_control
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.1.1 (2021-11-30)
------------------
* Remove the ds4drv dependency
* Fix the diagnostic analyzer node
* Rename BOXER_SERIAL_NO to ROS_ROBOT_SERIAL_NO to match with incoming changes to the ISO
* Squashed commit of the following:
  commit 1b05ec542302a034dc62f85bd28513b43ef17223
  Author: Chris Iverach-Brereton <civerachb@clearpathrobotics.com>
  Date:   Wed Nov 10 09:54:43 2021 -0500
  Remove old dependencies, add the joint state controller for use inside gazebo
  commit 6cef209cd4cef2212a11ff85a403b9408fbc9054
  Author: Chris Iverach-Brereton <civerachb@clearpathrobotics.com>
  Date:   Tue Nov 9 17:18:26 2021 -0500
  Add gazebo plugin definitions for the realsense, front & rear lidars. Move the IMU configuration into the sensors file
  commit 5141445c9a09713e9a17f0501f1805c1092c4a3b
  Author: Chris Iverach-Brereton <civerachb@clearpathrobotics.com>
  Date:   Tue Nov 9 17:17:36 2021 -0500
  Adjust the velocity controller and friction properties to get the robot to steer better in gazebo when using the game controller. It's still a bit sluggish when turning, but better than it was
  commit 8a031d0163be02efe809fb02b3ef04f5e3865ab3
  Author: Chris Iverach-Brereton <civerachb@clearpathrobotics.com>
  Date:   Tue Nov 9 16:07:25 2021 -0500
  Add relays so that the twist_mux output can talk to gazebo's cmd_vel input
  commit cdbe72bb1704d5847f1c42f5e0459d3cfa406bda
  Author: Chris Iverach-Brereton <civerachb@clearpathrobotics.com>
  Date:   Tue Nov 9 13:24:32 2021 -0500
  Start progress on getting the Gazebo simulation of the new boxer to work correctly
* Always start the teleop nodes as part of control.launch
* Contributors: Chris Iverach-Brereton

0.1.0 (2021-11-08)
------------------

* Initial commit of for Noetic

0.0.8 (2019-08-29)
------------------

0.0.7 (2019-08-22)
------------------
* Added a top frame and fixed diagnostics dependency
* Contributors: Dave Niewinski

0.0.6 (2018-12-20)
------------------
* Pulled well back on teleop until PS4 bug is fixed.
* Added extra config layer to control
* Contributors: Dave Niewinski

0.0.5 (2018-11-15)
------------------
* Updated acceleration to make the system more responsive
* Contributors: Dave Niewinski

0.0.4 (2018-11-07)
------------------
* Updated localization
* Contributors: Dave Niewinski

0.0.3 (2018-11-06)
------------------
* Fixed install
* Contributors: Dave Niewinski

0.0.2 (2018-11-05)
------------------
* Fixed dependencies
* Contributors: Dave Niewinski

0.0.1 (2018-10-31)
------------------
* Initial ish commit
* Contributors: Dave Niewinski
