# Traffic_automation
 This model detect and classify the vehicle into their classes using tensorflow.
 
 This model is basically used to automate the traffic according to vehicle density and extra preference given to ambualnce i.e. it will open that firstly in which ambulance is detected.
 
I have make this model using tensorflow.
Main steps in this project:
1. collecting the  trafficimages.
classify them into two train and test images int 9:1 ratio.
2. converting all of them into equal sizes using image_resolution.py flle
3. Labelling all the images.
4. converting all xml files(which is created after labelling) into csv files using xml_to_csv.py
   This is done for both train and test xml files. 
5. Generating tf record files using tf_records.py(labelmap.pbtxt and faster_rcnn_resnet50_pets.config is used in this tfrecord files i.e. we have to give path of these files where it is askedi generate_tfrecord.py file.
6.  

