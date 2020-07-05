# Abandoned-Object-Detection
It is the  automatic detection of objects that are abandoned or removed in a video scene is an interesting area of computer vision + Image Procesing, with key applications in video surveillance.

#### Work to be done :
* We are processing the live feed of the CCTV camera with image processing.
* If a person is releasing off some piece of luggage the camera will catch the activity.
3.This frames are been detected and been image processed by Edge detection . The processing is done by the OpenCV.
4.If the bag is untouched for a some period of time the analyser decides and further gives an alarm to the authority.

#### Steps performed:
1.The input video is divided into frames.
2.The first frame is converted to Grey from RGB.
3.The video is converted to Grey from RGB.
4.Frame difference of first frame and the video is taken.
5.Canny Edge Detection is applied.
6.A timer is started in case of a detection.
7.If the abandoned object is not moved for a specified time then it is displayed on the screen.


