# YOLOv3-image-detection

This AIM of this repository is to make the create an application using Deep Learning based Object Detection using YOLOv3 with OpenCV

YOLO trained on the COCO dataset. The COCO dataset consists of 80 labels. You can fetch the weights from the link below (beacause of the large size i did not uplaod here)
https://github.com/pjreddie/darknet/blob/master/data/coco.names

https://pjreddie.com/darknet/yolo/

The directories structure should as follow:

yolo-coco-data/
 : The YOLOv3 object detector pre-trained (on the COCO dataset) model files. These were trained by the Darknet team should be kept here.

images/
 : This folder should contain static images which we will be used to perform object detection on for testing and evaluation purposes.

videos/
 : This directory should contains sample test videos for testing. After performing object detection with YOLO on video, we’ll process videos in real time camera input. 

output/
 : Output videos that have been processed by YOLO and annotated with bounding boxes and class names will appear at this location.

# RESULT
![image](https://user-images.githubusercontent.com/46977634/80388315-a5250380-88a1-11ea-9a87-163e2fdd57c6.png)


Objects Detection took 1.88191 seconds
Object 1: person
Object 2: person
Object 3: person
Object 4: person
Object 5: person
Object 6: person
Object 7: person
Object 8: tie
Object 9: person
Object 10: person
Object 11: person
Object 12: laptop
Object 13: tie
Object 14: cup
Object 15: cup
Object 16: tie
Object 17: laptop

Total objects been detected: 24
Number of objects left after non-maximum suppression: 17
