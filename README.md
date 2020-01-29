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
   This is done ,for both train and test xml files. 
5. Generating tf record files using tf_records.py(labelmap.pbtxt and faster_rcnn_resnet50_pets.config is used in this tfrecord files i.e. we have to give path of these files where it is ask generate_tfrecord.py file.
6. Then train the model and model was created with name my_exp_graph.
7. Then test the model with images and videos which you want.

Note:
For training purpose gpu in laptop required,if it is not present then use google colab.I had used google colab for my project.
Google colab provide you gpu online and other libraries which you want, you just have to import.

For watching output, link:  https://www.youtube.com/watch?v=zcCWJ-Tb8fc
Thanks

