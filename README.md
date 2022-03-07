# YOLO-Object-recognition-with-QT
Objection recognition is done in QT using OpenCV and YOLO ( you only look once) algorithm. The language used is C++. A GUI application made is user friendly.
This is an algorithm that detects and recognizes various objects in a picture (in real-time). The YOLO algorithm works by dividing the image into N grids, each having an equal dimensional region of SxS. Each of these N grids is responsible for the detection and localization of the object it contains.

YOLOv3 is used in this project. It was trained on COCO dataset which has over 80 classes.
Performance with CPU as the target we can only process some frames per second(3fps approx), but its easy to configure. On the other hand, using GPU increases the speed to 45fps.

The GUI application is made through Qtgui. It enables user to give image input, video input as well as real time camera input through webcam. User can give input through command line arguments or he/she can select the file from directory
