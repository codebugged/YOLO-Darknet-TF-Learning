# YOLO-Darknet-TF-Learning
YOLO Family Custom Object Detection Transfer Leaning Pipeline

##Steps to follow

1. Create yolov4-tiny and training(inside yolov4-tiny) folders in your google drive
2. Create & upload the files we need for training ( i.e. “obj.zip” , “yolov4-tiny-custom.cfg”, “obj.data”, “obj.names” and “process.py” ) to your drive
3. Mount drive and link your folder
4. Make changes in the Makefile to enable OPENCV and GPU
5. Run make command to build darknet
6. Copy the files “obj.zip”, “yolov4-tiny-custom.cfg”, “obj.data”, “obj.names”, and “process.py” from the yolov4-tiny folder to the darknet directory in Colab VM
7. Run the process.py python script to create the train.txt & test.txt files
8. Download the pre-trained YOLOv4-tiny weights
9. Train the detector
10. Check performance
11. Test your custom Object Detector
