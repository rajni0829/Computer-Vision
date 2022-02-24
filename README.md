## TASK-I: 
Problem Statement: Given a video, figure out frames of interest & categories appearing in that micro-batch segment.  
**Tech Stack Used :**  
--> Model: OpenCv  
--> Packages: Numpy, Glob, OpenCv, Ftp, MatplotLib, Keras, Tensorflow  
--> Dataset: https://drive.google.com/file/d/15exOnwxii9NlPRxrkW03AFkncAmvNRnf/view?usp=sharing  

Here, I'm taking a video as the i/p and after running the file, a folder named Extracted_Pics is created and snapshots taken from Video is saved. Additionally, Part-II does the naming of the objects detected in the video.  

## TASK-II: 
Given an image, detect objects in the frame & predict their category class.  
Since we're free to use any dataset,there exists 2 Problem Statements.   
- Approach-I : Where we can pre-process image, train dataset for multiple images and pass on an image from Test Dataset which has single object and can predict, to which class the object belongs.      
**Tech Stack Used:**  
--> Model: VGG16 – Convolutional Neural Network  
--> Packages: Numpy, PIL, MatplotLib, Pandas, Keras, Tensorflow  
--> Dataset: https://drive.google.com/drive/folders/1eb73db_Ib4mk3KjdyY7AvoOy9JyLOkYE?usp=sharing


- Approach-II : We have a data(where there's an image containing multiple objects) and we need to detect what are these objects from a single frame and to which class each belong.  

I've taken both the statements into consideration and tried implementing as per my understanding.



References :  
https://github.com/opencv/opencv/wiki/TensorFlow-Object-Detection-API
https://machinelearningmastery.com/object-recognition-with-deep-learning/  
https://youtu.be/irHhDMbw3xo  
https://machinelearningmastery.com/how-to-train-an-object-detection-model-with-keras/  
https://scikit-learn.org/dev/modules/generated/sklearn.preprocessing.OneHotEncoder.html?highlight=onehotencoder#sklearn.preprocessing.OneHotEncoder  
https://gist.github.com/dkurt/54a8e8b51beb3bd3f770b79e56927bd7  
Thanks.   

