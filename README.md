# Marlin-Bugfix-2.0.x configuration files for the SKR mini e3 v1.2 board + BLTouch

In this repository are the configuration files I have used in attempt to set up the SKR mini e3 v1.2 board with the Antclabs BLTouch.

I've used [this guide](https://www.reddit.com/r/ender3/comments/e894j7/marlin_20x_guide_for_ender_3_using_skr_mini_e3_v12/) made by /u/qwewer1/

6/18/2020 - 
* ~~The probe currently fails after probing the first two points.~~   
* After reading [this comment](https://github.com/MarlinFirmware/Marlin/issues/17242#issuecomment-605541216) on a bug report, I checked my bed adjustment nuts, and one was loose. I tightened the nut, and the bed leveling worked as expected.

6/19/2020 - 
* I've used this [PID autotuning guide](https://www.reddit.com/r/3Dprinting/comments/h8xqrn/pid_autotune/) created by /u/qwewer1/. Updated the PID values in Configuration.h