# SmileDetection

Added video_test.launch to create an activity that reads stream from camera and publishes it to ROS.

Added image_converter.py to convert image stream to opencv image

Added smile_detect.py to detect faces and smiles in faces. It is topic that publishes the number of smiled faces

Added haarcascade_smile.xml and haarcascade_frontalface_default.xml. Big thanks to the guys who provided these resources online.

Use: roslaunch video_test.launch
to start reading from camera
Use: python smile_detect.py
to get the number of smiles that are detected by the haar face/smile detector



## INSTLALL ROS kinetic  DEPENCENDIES

```
sudo apt-get install ros-kinetic-catkin ros-kinetic-cv-bridge ros-kinetic-roslib ros-kinetic-rospy ros-kinetic-std-msgs
```
ERROR:
E: Unable to locate package ros-kinetic-cv2
E: Unable to locate package ros-kinetic-sensors-msgs
E: Unable to locate package ros-kinetic-sys
