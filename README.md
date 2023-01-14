# yolov4-things

## obj.names
classname_0<br> 
classname_1<br>
.<br>
.<br>
classname_n<br>


## train.txt
path_to_img_0<br>
path_to_img_1<br>
.<br>
.<br>
path_to_img_n<br>

## test.txt
similar to train.txt


### coco bbox - x_min, y_min, w, h
### yolo bbox - x_center, y_center, w, h

## yolo dataset format
dataset_folder<br>
&emsp;  0.jpg<br>
&emsp;  0.txt<br>
&emsp;  &emsp;  class_id, x_center, y_center, w, h<br>
&emsp;  &emsp;  .<br>
&emsp;  &emsp;  .<br>
&emsp;  &emsp;  class_id, x_center, y_center, w, h<br>
<br>
&emsp;  .<br>
&emsp;  .<br>
<br>
&emsp;  1.jpg<br>
&emsp;  1.txt<br>
&emsp;  &emsp;  class_id, x_center, y_center, w, h<br>
&emsp;  &emsp;  .<br>
&emsp;  &emsp;  .<br>
&emsp;  &emsp;  class_id, x_center, y_center, w, h<br>
&emsp;  .<br>
&emsp;  .<br>
&emsp;  n.jpg<br>
&emsp;  n.txt<br>
&emsp;  &emsp;  class_id, x_center, y_center, w, h<br>
&emsp;  &emsp;  .<br>
&emsp;  &emsp;  .<br>
&emsp;  &emsp;  class_id, x_center, y_center, w, h<br>
