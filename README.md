# UNDERWATER OBJECT DETECTION WITH YOLOV7 
YOLOv7 is a powerful object detection algorithm that is widely used for a variety of applications, including underwater object detection. Underwater environments pose unique challenges for object detection algorithms, such as low light conditions, refraction, and reflections.

To address these challenges, researchers have proposed various techniques for improving the accuracy of object detection algorithms in underwater environments. One such technique is to pre-process the underwater images to improve their quality, such as by correcting for color distortion or removing noise.

Another approach is to use specialized CNN architectures that are tailored for underwater object detection. For example, some researchers have proposed using multi-scale CNNs or CNNs with attention mechanisms to improve the performance of object detection algorithms in underwater environments.

Overall, YOLOv7 has shown promising results for underwater object detection, demonstrating high accuracy and efficient processing times. However, further research is needed to fully understand the limitations of YOLOv7 and to develop even more effective techniques for underwater object detection.

## IMAGE PROCESSING PROCESS
Data Collection: Objects prepared for the task are placed underwater in a pool environment. Underwater objects are recorded using a GoPro camera.

![image](https://user-images.githubusercontent.com/60732734/213562252-59aae302-1615-43e5-95cb-5c98786a2266.png)

Data Cleaning: The videos are split into photos using the VLC media player. Then, blurry and irrelevant images are removed.

Data Splitting: Dividing the data set into test, train, and validation allows for more effective use of the data during the training and testing of a machine learning model. In summary, the data set is divided into three main parts: test, train and validation.

![image](https://user-images.githubusercontent.com/60732734/213564759-db28c641-9dc6-44b3-93b3-17ef8179b62d.png)

Data Labeling: Data labeling is necessary for training learning algorithms in AI applications and it specifies the meaning, features or categories of the data sets. Objects detected on images were labeled using makeSense.ai for the task of identifying objects in the image.

![image](https://user-images.githubusercontent.com/60732734/213565156-5ad2ed44-90b5-4d63-9b28-bcacbb2df250.png)

Result graph of a model trained with yoloV7 :

![image](https://user-images.githubusercontent.com/60732734/213565444-0a99770b-936f-439e-a064-9a370c3299c0.png)

Video test result :

https://drive.google.com/file/d/1w5NaFFyPdeOAFbxki5hIpIyv7LnR8LqT/view?amp;usp=embed_facebook



