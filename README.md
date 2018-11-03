This program can be used to detect drowsiness for a given person. In this program wee check how long a person's eyes have been closed for. If the eyes have been closed for a long period i.e. beyond a certain threshold value, the program will alert the user by playing an alarm sound.

The program contains 3 files, which are
## Files
 - **face_and_eye_detector_single_image.py** - Detects face and eye from a single image.
 Demo-
 
|  ![Test Image](https://github.com/mohitwildbeast/Driver-Drowsiness-Detector/blob/master/images/test.jpeg)| ![Result Image](https://github.com/mohitwildbeast/Driver-Drowsiness-Detector/blob/master/images/result_face_detector_single_image.png) |
|--|--|
|  |  |

 - **face_and_eye_detector_webcam_video.py** - Detects face and eye in a webcam feed ![Webcam Face and Eye Detection](https://github.com/mohitwildbeast/Driver-Drowsiness-Detector/blob/master/images/webcam_face_eye_detect.jpeg)
 - **drowsiness_detect.py**- This script detects if person is drowsy or not using webcam video feed

> DEMO
![Drowsiness Detection Demo](https://github.com/mohitwildbeast/Driver-Drowsiness-Detector/blob/master/images/drowsiness_detector_demo.gif)
 
 ## Requirements
  

    numpy==1.15.2
	dlib==19.16.0
	pygame==1.9.4
	imutils==0.5.1
	opencv_python==3.4.3.18
	scipy==1.1.0
Use `pip install -r requirements.txt`to install the given requirements.

## Usage
