# Realtime circuit fault detection
This project uses computer vision to detect faults on a breadboard circuit.
A microscope scans the breadboard circuit and the model detects 
the input image for faults (faulty connections) in real time. A simple circuit image is shown below:
![S__9748514](https://github.com/chris199713/Power_electronics_fault_detection/assets/53930769/8dc4b2b4-515b-40f8-98b3-91c3c94aad88)
## Built with
* Labelimg
* OpenCV
* Tensorflow model zoo
  * SSD MobileNet V2 FPNLite 320x320
* Tensorflow object detection API
# Description

# Results
Using OpenCV and the USB microscope, a quick test of the model performance can be shown below using some images captured in real time.
![messageIm![messageImage_1704263788903](https://github.com/chris199713/Power_electronics_fault_detection/assets/53930769/c8aebc6f-6136-41fa-9988-6d436ca6d5a0)
age_1704263375616](https://github.com/chris199713/Power_electronics_fault_detection/assets/53930769/33f8e1b4-6c40-49d5-949f-386a494c2e1c)
![messageImage_1704262978300](https://github.com/chris199713/Power_electronics_fault_detection/assets/53930769/45fbd857-3ef3-40df-821b-a466dbf26c2d)
![messageImage_1704264009792](https://github.com/chris199713/Power_electronics_fault_detection/assets/53930769/1c2faa04-c7b2-4f7f-9158-b74070a4acf6)
# Acknowledgements
Resources I used for this project
* [Tensorflow object detection](https://www.youtube.com/watch?v=pDXdlXlaCco&t=1703s)
* [Labelimg](https://github.com/HumanSignal/labelImg)
* [OpenCV](https://github.com/opencv/opencv)
* [Tensorflow object detection model zoo](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf2_detection_zoo.md)
