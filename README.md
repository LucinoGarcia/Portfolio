# Brain-Controlled Prosthetic Gesture Classification
- Created a convolutional neural network to classify EEG signals to control a UR5e robot arm, serving as a brain-controlled prosthetic.
- Collected 1000 EEG samples for each of the four predetermined gestures and a negative classification using an OpenBCI Electrode Cap. Manually verified and filtered EEGs using a Buttersworth filter.
- Initially explored Decision Trees and various machine learning techniques, resulting in accuracies close to random guessing (~20%). Opted for a CNN due to its effectiveness with spatial data.
- Chose accuracy as the performance metric due to balanced classes and safety considerations for the robot arm. Achieved a model accuracy of 92% with the CNN.
- Despite the promising accuracy, the project was complex and prone to errors, particularly during data collection. The CNN's numerous tunable parameters and signal processing steps required meticulous, isolated parameter tuning for optimization.

![Image](/images/BME_CM.png)

[Brain-Controlled Prosthetic Gesture Classification’s GitHub Repository](https://github.com/LucinoGarcia/Robot-Arm-Classification)



# Disease Detection with Computer Vision
- Developed a 3D U-Net model for classifying tumors in DICOM format MRI data.
- Data was provided by the Decathlon 10 Challenge but required patching and standardization.
- A 3D U-Net model was chosen for its architecture optimized for volumetric datasets. Soft Dice was used as the loss function, and Dice Coefficient was used as the metric.
- Utilized both sensitivity and specificity as measures of model evaluation. Sensitivity and specificity varied by samples but typically exceeded 85% sensitivity and 90% specificity.
- A 3D U-Net model can definitely be utilized for cancerous tissue classification—even with samples in the hundreds. It should generalize nicely after being trained on additional datasets.

![image](/images/3_View.png)

[Disease Detection with Computer Vision’s GitHub Repository](https://github.com/LucinoGarcia/MRI-Brain-Tumor-Detection)




# Bitcoin Price Regression Prediction


# Clustering and Segmentation for Banking Customers




# In-Progress
### SQL project
### Tableau dashboard
