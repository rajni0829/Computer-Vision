# Detecting Objects from Video
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

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![Image of objects](/TASK-1/Method-1/DancingCat.gif)   
I've taken both the statements into consideration and tried implementing as per my understanding.  


## TASK-II: 
Given an image, detect objects in the frame & predict their category class.  
Dataset has been splitted into training, testing and the image is pre-processed, trained for multiple images,then the image is passed on from Test Dataset which has single object and class of object can be predicted.   


## Tech Stack Used :    
--> Model: VGG16 – Convolutional Neural Network, OpenCv    
--> Packages: Numpy, Glob, OpenCv, Ftp, MatplotLib, Keras, Tensorflow   
--> Dataset: https://drive.google.com/file/d/15exOnwxii9NlPRxrkW03AFkncAmvNRnf/view?usp=sharing   


## References :  
https://github.com/opencv/opencv/wiki/TensorFlow-Object-Detection-API
https://machinelearningmastery.com/object-recognition-with-deep-learning/  
https://youtu.be/irHhDMbw3xo  
https://machinelearningmastery.com/how-to-train-an-object-detection-model-with-keras/  
https://scikit-learn.org/dev/modules/generated/sklearn.preprocessing.OneHotEncoder.html?highlight=onehotencoder#sklearn.preprocessing.OneHotEncoder  
https://gist.github.com/dkurt/54a8e8b51beb3bd3f770b79e56927bd7   

Thanks.   

