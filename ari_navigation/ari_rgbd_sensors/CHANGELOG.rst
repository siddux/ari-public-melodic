^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package ari_rgbd_sensors
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.0.36 (2022-11-17)
-------------------

0.0.34 (2022-07-31)
-------------------
* noetic compat
* Contributors: Séverin Lemaignan

0.0.33 (2021-10-18)
-------------------
* Merge branch 'fix-head-camera-launch' into 'ferrum-devel'
  fix-head-camera-launch
  See merge request robots/ari_navigation!34
* fix typo
* fix-head-camera-launch
* Contributors: federiconardi, sergiomoyano

0.0.32 (2021-09-02)
-------------------
* Merge branch 'fix-enable-infra' into 'ferrum-devel'
  fix-enable-infra
  See merge request robots/ari_navigation!33
* Update torso_front_camera.launch
* Contributors: federiconardi, sergiomoyano

0.0.31 (2021-07-30)
-------------------
* Merge branch 'startup_laser_fixes' into 'ferrum-devel'
  Use robot_info instead of replaces
  See merge request robots/ari_navigation!32
* Take care of false as a boolean
* Use robot_info instead of replaces
* Contributors: davidfernandez, saikishor

0.0.30 (2021-07-28)
-------------------
* added filters to realsense head and torso cameras to clean the pointcloud
* Contributors: antoniobrandi

0.0.29 (2021-05-31)
-------------------
* Merge branch 'initial-reset-front-camera' into 'ferrum-devel'
  Initial reset front camera on start
  See merge request robots/ari_navigation!28
* Initial reset front camera on start
  This is needed in the event the USB driver is reloaded.
  See https://github.com/IntelRealSense/librealsense/issues/9099 for more
  details
* Contributors: Victor Lopez, federiconardi

0.0.28 (2021-05-20)
-------------------
* Merge branch 'ferrum-devel' of gitlab:robots/ari_navigation into laser2
* Contributors: sergiomoyano

0.0.27 (2021-04-07)
-------------------
* Merge branch 'head-realsense' into 'ferrum-devel'
  Add head realsense launcher
  See merge request robots/ari_navigation!24
* adjust head front camera topic
* Simplify head rgbd launcher
* Add head realsense launcher
* Contributors: Sara Cooper, davidfernandez, procopiostein

0.0.26 (2021-03-16)
-------------------
* Merge branch 'ferrum-devel' of gitlab:robots/ari_navigation into ferrum-devel
* Contributors: Software Engineer

* Merge branch 'ferrum-devel' of gitlab:robots/ari_navigation into ferrum-devel
* Contributors: Software Engineer

* Merge branch 'ferrum-devel' of gitlab:robots/ari_navigation into ferrum-devel
* Contributors: Software Engineer

* Merge branch 'ferrum-devel' of gitlab:robots/ari_navigation into ferrum-devel
* Contributors: Software Engineer

0.0.24 (2021-01-19)
-------------------
* Merge branch 'throttle-fisheye' into 'ferrum-devel'
  Add throttle when remapping fisheye topics
  See merge request robots/ari_navigation!22
* Add throttle when remapping fisheye topics
* Merge branch 'elp-relay' into 'ferrum-devel'
  Elp relay
  See merge request robots/ari_navigation!21
* Add service remapping
* Add camera info relay
* Add jetson fisheye cameras relay
* Contributors: Sara Cooper, federiconardi, procopiostein, victor

0.0.23 (2020-11-17)
-------------------

0.0.22 (2020-09-01)
-------------------

0.0.21 (2020-08-17)
-------------------

0.0.20 (2020-08-07)
-------------------
* Merge branch 'exposure' into 'ferrum-devel'
  Exposure controls on master_calib
  See merge request robots/ari_navigation!19
* Exposure controls on master_calib
* Contributors: davidfernandez, luca

0.0.19 (2020-07-28)
-------------------
* Merge branch 'presets-config' into 'ferrum-devel'
  updating config to high accuracy preset
  See merge request robots/ari_navigation!18
* updating config to high accuracy preset
* Contributors: Federico Nardi, federiconardi

0.0.18 (2020-06-30)
-------------------

0.0.17 (2020-06-25)
-------------------

0.0.16 (2020-06-23)
-------------------
* modified torso_front_camera.launch to get json and set proper image sizes
* Contributors: Federico Nardi

0.0.15 (2020-06-16)
-------------------
* Fix camera_info from raspi
* Contributors: Victor Lopez

0.0.14 (2020-06-11)
-------------------
* Merge branch 'json-load' into 'ferrum-devel'
  added loading of json file
  See merge request robots/ari_navigation!15
* added loading of json file
* Contributors: Federico Nardi, procopiostein

0.0.13 (2020-06-02)
-------------------
* Merge branch 'no-rgbd-laser' into 'ferrum-devel'
  removing rgbd laser scan
  See merge request robots/ari_navigation!14
* removing rgbd laser scan
* Contributors: Federico Nardi, procopiostein

0.0.12 (2020-05-26)
-------------------
* Merge branch 'frame-skip' into 'ferrum-devel'
  setting pointcloud_frame_skip parameter
  See merge request robots/ari_navigation!13
* Merge branch 'small-map' into 'ferrum-devel'
  added small-textured-office map
  See merge request robots/ari_navigation!12
* added new map for simulated environment + updated image topics
* setting pointcloud_frame_skip parameter
* Contributors: Federico Nardi, procopiostein

0.0.11 (2020-05-20)
-------------------
* Merge branch 'fixed-depth-proc' into 'ferrum-devel'
  added launch file for registering rgb and depth
  See merge request robots/ari_navigation!11
* added launch file for registering rgb and depth
* Merge branch 'depth-image-proc' into 'ferrum-devel'
  Depth image proc
  See merge request robots/ari_navigation!10
* Remove unecessary parts in depth_proc launch
* Update to create depth registered image topic
* Depth image processing launch file to produce /depth_registered/points topic
* Contributors: Sara Cooper, federiconardi, procopiostein

0.0.10 (2020-03-17)
-------------------
* better ls2pc config
* Contributors: Procópio Stein

0.0.9 (2020-03-13)
------------------
* Fix relay topic name
* Use relay instead of republish for raspi images, saves a lot of CPU
* Merge branch 'add-elp-launch' into 'ferrum-devel'
  added elp launch and dep for front camera
  See merge request robots/ari_navigation!7
* Parametrize elp_front.launch
* Update elp_front.launch
* Removed comments, set as arguments remaining parameters
* Add argument to set device
* Add device id to launch file
* missing format param
* added simple launch for elp
* added elp launch and dep for front camera
* Contributors: Procópio Stein, Victor Lopez, procopiostein, saracooper

0.0.8 (2020-02-11)
------------------
* removed virtual tf for laser from camera
* fixed input cloud name
* updated default args for launches
* Modified and created the structure for navigation for ARI adding the localization move_base state_machine
* added files for PC2LS
* Contributors: Procópio Stein, alessandrodifava

0.0.7 (2020-01-09)
------------------
* Add missing dependencies
* Contributors: Victor Lopez

0.0.6 (2020-01-09)
------------------
* Add head_front_camera launch
* Contributors: Victor Lopez

0.0.5 (2020-01-07)
------------------
* Merge branch 'ari_calib_odom_in_file' into 'erbium-devel'
  Ari calib odom in file
  See merge request robots/ari_navigation!3
* New odom in calib file with axis angle representation and the right axis chosen
* Configured the file for the odom in
* Contributors: Victor Lopez, alessandrodifava

0.0.4 (2019-12-17)
------------------
* Merge branch 'ari_back_camera_tf_fixing' into 'erbium-devel'
  Adding the static transformation for tf and removing the odom_tf publish to fix the tf structure
  See merge request robots/ari_navigation!1
* Adding the static transformation for tf and removing the odom_tf publish to fix the tf structure
* Contributors: Victor Lopez, alessandrodifava

0.0.3 (2019-11-08)
------------------
* Update front camera launch
* Initial commit
* Contributors: Victor Lopez
