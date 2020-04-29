# AE4317
This code makes use of the tensorflow package. 

The following files need to be added to the Object_Detection Folder:
1) labelmap.pbtxt
2) frozen_inference_graph.pb
3) Object_detection_image.py


The program is run by exectuing Object_detection_image.py in the directory tensorflow/models/research/object_detection.
The execution format is as follows: python object_detection_image.py (image filepath)

The code generates a list (objBBL) which contains the lists of coordinates of the different detected objects' bounding boxes.
The original image is also displayed with the bounding boxes drawn and the corrosponding percentage certainty labelled on the image.
