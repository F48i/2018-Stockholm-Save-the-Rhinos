# 2018-Stockholm-Save-the-Rhinos
Openhack code for humanity

Teamname: Save the Rhino's

Chosen case: Peace Parks

Solution: Raspberry Sensor Mesh Network 

Get started with your develop environment: 

1.) Fresh Raspberry Pi Raspbian installation

For face recognition:

2.) Install OpenCV, used instruction from: 
https://www.pyimagesearch.com/2017/09/04/raspbian-stretch-install-opencv-3-python-on-your-raspberry-pi/

3.) Install raspicam libary:
https://github.com/cedricve/raspicam 

4.) Face recognition example: 
https://github.com/andygrove/raspicam-facedetect-cpp

5.) Small changes for OpenCV4 (fork of the project above)
https://github.com/F48i/raspicam-facedetect-cpp

Build and run raspicam-facedetection-cpp
./build.sh

$ ./opencv_example --cascade="/home/pi/Downloads/opencv/data/haarcascades/haarcascade_frontalface_alt.xml" --nested-cascade="/home/pi/Downloads/opencv/data/haarcascades/haarcascade_eye_tree_eyeglasses.xml" --scale=1.3

or

$ ./opencv_example --cascade="/home/pi/Downloads/opencv/data/haarcascades/haarcascade_frontalface_alt.xml" --scale=1.3

Note might need to fix some install paths ;-)

Languages used: C++

Team members: Fabian Kunkel, Carmen Beltran
