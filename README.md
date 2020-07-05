# Abandoned-Object-Detection
It is the  automatic detection of objects that are abandoned or removed in a video scene is an interesting area of computer vision + Image Procesing, with key applications in video surveillance.

#### Work to be done :
* We are processing the live feed of the CCTV camera with image processing.
* If a person is releasing off some piece of luggage the camera will catch the activity.
* This frames are been detected and been image processed by Edge detection . The processing is done by the OpenCV.
* If the bag is untouched for a some period of time the analyser decides and further gives an alarm to the authority.

#### Steps performed:
* The input video is divided into frames.
* The first frame is converted to Grey from RGB.
* The video is converted to Grey from RGB.
* Frame difference of first frame and the video is taken.
* Canny Edge Detection is applied.
[Canny Edge](https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_imgproc/py_canny/py_canny.html)

* A timer is started in case of a detection.
* If the abandoned object is not moved for a specified time then it is displayed on the screen.


