## TASK-I: 
Problem Statement: Given a video, figure out frames of interest & categories appearing in that micro-batch segment.  

"# Object-Detection-From-Video"

## TASK-II: 
Given an image, detect objects in the frame & predict their category class.  
Since we're free to use any dataset,there exists 2 Problem Statements.   
- Approach-I : Where we can pre-process image, train dataset for multiple images and pass on a test image from Test Dataset which has single object and can predict to which class it belongs.

- Approach-II : We have a data(where there's an image containing multiple objects) and we need to detect what are these objects from a single frame and to which class each belong.  

I've taken both the statements into consideration and tried implementing as per my understanding.



References :  
https://machinelearningmastery.com/object-recognition-with-deep-learning/  
https://youtu.be/irHhDMbw3xo  
https://machinelearningmastery.com/how-to-train-an-object-detection-model-with-keras/  
https://scikit-learn.org/dev/modules/generated/sklearn.preprocessing.OneHotEncoder.html?highlight=onehotencoder#sklearn.preprocessing.OneHotEncoder  
