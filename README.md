# RoboND_Project_Robotic_Inference

The Project explores an embedded robotics inference system, leveraging Nvidia�s Deep Learning tools, to create models on a DIGITS workflow platform that can be deployed in real time robotics applications. Real time image analysis and recognition of different features of Indian Bank Currency Notes� Original and Fake, using GoogLeNet neural network has been proposed.

## Data Acquisition

The Data Acquisition details in Training and Validation Image set can be represented as below:

![Supplied Dataset](RoboND_Project_Robotic_Inference/Results/Supplied Dataset/Data_Acquisition.png)

![Collected INR Dataset](RoboND_Project_Robotic_Inference/Results/Collected Dataset/Data_Acquisition.png)

## Results 

The results on Accuracy and Inference Time for supplied dataset:

![Supplied Dataset Accuracy](RoboND_Project_Robotic_Inference/Results/Supplied Dataset/Accuracy_InferenceTime_Supplied_Dataset.jpg)

Following curve shows the training loss, validation loss and accuracy levels for the INR Currency banknotes datasets, with a GoogLeNet architecture:

![INR Banknotes Dataset Accuracy](RoboND_Project_Robotic_Inference/Results/Collected Dataset/Accuracy_Curve_INR_Currency_Model.jpg)

The prediction on test dataset with the trained classification model accurately determines all the test images with over 90% accuracy levels. The resulting predictions on test dataset is shown below: 

![Prediction on INR Banknotes Test Dataset](RoboND_Project_Robotic_Inference/Results/Collected Dataset/Prediction Results_INR Currency Model.jpg)

Hence we have our own Inference system for recognizing bank notes, one of the vital areas of research to prevent banknotes forgery, theft and currency frauds !!