# amur_leopard_dataset
This is the dataset of one of the most critically endangered species Amur Leopard, that i collected to train my own amur-leopard detector using [TensorFlow's Object Detection API](https://github.com/tensorflow/models/tree/master/research/object_detection). The total dataset consists of 200 images that i collected from google and labelled it using [Label Img](https://github.com/tzutalin/labelImg). I used 160 images for training and 40 images for validation.

##### Folder Structure:
```
+ annotations: contains the xml files in PASCAL VOC format
+ CSV's: contains the label files (csv)
+ train-images: contains the training image data in jpg format
+ test-images: contains the testing image data in jpg format
+ training: contains the pipeline configuration file and labelmap file
- a few scripts: generate_tfrecord.py is used to generate the input files
for the TesorFlow API and xml_to_csv.py is used to convert the xml files into one csv
- a few jupyter notebooks: draw outline is used to plot some of the data and 
Amur_Leopard_Detection_Live_Tutorial is tutorial to test your model live using OpenCV.
```
