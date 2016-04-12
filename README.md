# FYP_3D_Reconstruction

Dense 3D Reconstruction from UAV camera images.

Collaborative Final Year Project by Wenxin Liu and Xuelai Sun. HKUST.

#### TODO (Sun): Multi-cam reconstruction
#### TODO (Liu): Bundle Adjustment

* [fyp_3d_reconstruction] is the package src file. Should be put at path/to/catkin_ws/src/
* [minutes] includes meeting records
* [photos] includes picture resources

### How to run the program:
1. changes the folder path of photos to your directory in main.cpp
2. run `roscore` in a new terminal 
3. run `rosrun fyp_3d_reconstruction fyp_3d_reconstruction` in a new terminal
4. run `rosrun rviz rviz` in a new terminal
5. rewrite rviz frame to __/world_frame__ and press __add__ button at the lower left to choose marker topics to display

### Files specification:
* __fyp_3d_reconstruction__: multi-cam, with problem, can run

(under _Wenxin:)
* __fyp_3d_reconstruction_incomplete__: multi-cam, cannot run, a newer version of __fyp_3d_reconstruction__
* __fyp_3d_reconstruction_May_5__: 2-view, complete
* __fyp_3d_reconstruction__: bundle development on __fyp_3d_reconstruction_May_5__, partially done, can run
