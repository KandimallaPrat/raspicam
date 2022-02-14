# RaspiCam
----------
ROS melodic and noetic package for RaspberryPi Camera Streaming.

Built on [UbiquityRobotics'](https://github.com/UbiquityRobotics/raspicam_node) Raspberry Pi package. This repository contains the dependencies and some updates to the Ubiquity package, required to install and run PiCamera streaming on ROS base.

### Installation Instructions
These steps should be followed after you have installed ROS and set up your project workspace. 

1) Clone this repository into the ```src``` folder of your ROS workspace. 
2) Build this package using ```catkin_make```, while in your main ROS workspace folder.

### Running the Node
Detailed instructions are provided [here](https://github.com/KandimallaPrat/raspicam/tree/master/raspicam_node#readme). 

For a V2.x camera, run `roslaunch raspicam_node camerav2_1280x960.launch`

For a V1.x camera, run `roslaunch raspicam_node camerav1_1280x960.launch`

### Additional Information 
You might have to copy the [camera_info](https://github.com/KandimallaPrat/raspicam/tree/master/raspicam_node/camera_info) file into your ```.ros``` folder. 


Please blame me (and let me know) if you encounter any errors during installation or running of the nodes.
