^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package imu_compass
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.0.3 (2013-10-24)
------------------
* Populate the curr_heading_float message with the declination-corrected heading value.
* Add declination param and topic input to imu_compass node.
* Add dependency on scipy for compute script.
* Initialize curr_imu_reading_ with an empty message to avoid startup segfault.

0.0.2 (2013-10-04)
------------------
* adding rosparams for critical variables
* tuning covariance to rely more on gyro

0.0.1 (2013-09-23)
------------------
* creating new package for imu_compass
* added imu_compass.cpp, used to be called um6_compass when it came from https://github.com/clearpathrobotics/um6/tree/compass_cleanup/src
