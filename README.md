# Lucino's Data Science Portfolio

<div style="text-align: center;">
  <p>I am a Data Scientist and US Army veteran. I utilize machine learning techniques to extract meaningful narratives from data and construct predictive models – especially in open-source medical contexts.</p>
  <br>
  <a href="https://www.linkedin.com/in/lucino-garcia/">LinkedIn.com/in/Lucino-Garcia</a> <br>
  <a href="https://github.com/LucinoGarcia">GitHub.com/LucinoGarcia</a> <br>
  <a href="mailto:LGarciaJr@fastmail.com">LGarciaJr@fastmail.com</a>
</div>
 

[![Linked-In Icon](/images/icon-linkedin-20.png)](https://www.linkedin.com/in/lucino-garcia/) <a href="https://www.linkedin.com/in/lucino-garcia/">LinkedIn.com/in/Lucino-Garcia</a> <br>
[![Linked-In Icon](/images/icon-linkedin.png)](https://www.linkedin.com/in/lucino-garcia/) <a href="https://www.linkedin.com/in/lucino-garcia/">LinkedIn.com/in/Lucino-Garcia</a> <br>



<!-- [![Alt text](image_url) width=XX](link_url) -->
<!-- <img align="right" src="/images/3D_U-Net_Model_Diagram.png" width="178px"> -->






## Brain-Controlled Prosthetic Gesture Classification
- Created a convolutional neural network to classify EEG signals to control a UR5e robot arm, serving as a brain-controlled prosthetic.
- Collected 1000 EEG samples for each of the four predetermined gestures and a negative classification using an OpenBCI Electrode Cap. Manually verified and filtered EEGs using a Buttersworth filter.
- Initially explored Decision Trees and various machine learning techniques, resulting in accuracies close to random guessing (~20%). Opted for a CNN due to its effectiveness with spatial data.
- Chose accuracy as the performance metric due to balanced classes and safety considerations for the robot arm. Achieved a model accuracy of 92% with the CNN.
- Despite the promising accuracy, the project was complex and prone to errors, particularly during data collection. The CNN's numerous tunable parameters and signal processing steps required meticulous, isolated parameter tuning for optimization.

![Image](/images/BME_CM.png)

[GitHub Repository for Brain-Controlled Prosthetic Gesture Classification](https://github.com/LucinoGarcia/Robot-Arm-Classification)
<br><br><br>

[Link to another page](./Brain-Controlled-Prosthetic-Gesture-Classification.html).


## Disease Detection with Computer Vision
- Developed a 3D U-Net model for classifying tumors in DICOM format MRI data.
- Data was provided by the Decathlon 10 Challenge but required patching and standardization.
- A 3D U-Net model was chosen for its architecture optimized for volumetric datasets. Soft Dice was used as the loss function, and Dice Coefficient was used as the metric.
- Utilized both sensitivity and specificity as measures of model evaluation. Sensitivity and specificity varied by samples but typically exceeded 85% sensitivity and 90% specificity.
- A 3D U-Net model can definitely be utilized for cancerous tissue classification—even with samples in the hundreds. It should generalize nicely after being trained on additional datasets.

![image](/images/3_View.png)

[See more of the "Disease Detection with Computer Vision" project](./MRI-CVision.html).

<br><br><br>

# Bitcoin Price Regression Prediction
In-Progress






# Clustering and Segmentation for Banking Customers
In-Progress



<!-- Excel, Dashboard, Transportation -->
<!-- Excel, Dashboard, Coffee -->
<!-- Tableau, Dashboard, Coursera -->
<!-- SQL, YouTube -->

