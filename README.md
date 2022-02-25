_**Consider Only Fisrt 2 files as Completed**_

## TASK-I: 
_Problem Statement: Given a video, figure out frames of interest & categories appearing in that micro-batch segment._  
Since we're free to use any dataset, I've divided this section in 2 Methods.  
 
- **Method - I** :  If we're asked to detect Frames and recognize the object class.     
&nbsp;&nbsp; -->  It uses Detection Model of OpenCV and displays the frame and name of Object in the Video.  
&nbsp;&nbsp; -->  Input Data:  Any picture, gif or Video (Road_Traffic.gif/ Food Chain.mp4).    
&nbsp;&nbsp; -->  Output: Frame and Name of Object while playing the Video.    

- **Method - II** : If we'are given with a video data and asked to detect the Objects in the frame.   
&nbsp;&nbsp; --> This method will simply take snapshots from the video.  
&nbsp;&nbsp; --> Input Data: I'm taking a random video as the input file (Food_chain.mp4).    
&nbsp;&nbsp; --> Output: After running the given code, a folder named Extracted_Pics is created and snapshots taken from Video at every 5ms is saved.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![Image of objects](/TASK-1/Method-1/Road_Traffic.gif)


## TASK-II: 
Given an image, detect objects in the frame & predict their category class.  
- Approach-I : Where we can pre-process image, train dataset for multiple images and pass on an image from Test Dataset which has single object and can predict, to which class the object belongs.      


- Approach-II : We have a data(where there's an image containing multiple objects) and we need to detect what are these objects from a single frame and to which class each belong.  

I've taken both the statements into consideration and tried implementing as per my understanding.

**Tech Stack Used :**  
--> Model: VGG16 – Convolutional Neural Network, OpenCv   
--> Packages: Numpy, Glob, OpenCv, Ftp, MatplotLib, Keras, Tensorflow  
--> Dataset: https://drive.google.com/file/d/15exOnwxii9NlPRxrkW03AFkncAmvNRnf/view?usp=sharing 


References :  
https://github.com/opencv/opencv/wiki/TensorFlow-Object-Detection-API
https://machinelearningmastery.com/object-recognition-with-deep-learning/  
https://youtu.be/irHhDMbw3xo  
https://machinelearningmastery.com/how-to-train-an-object-detection-model-with-keras/  
https://scikit-learn.org/dev/modules/generated/sklearn.preprocessing.OneHotEncoder.html?highlight=onehotencoder#sklearn.preprocessing.OneHotEncoder  
https://gist.github.com/dkurt/54a8e8b51beb3bd3f770b79e56927bd7   

Thanks.   

