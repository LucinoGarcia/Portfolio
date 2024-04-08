# Lucino's Data Science Portfolio

<div style="text-align: center;">
  <p>I am a Data Scientist and US Army veteran. I utilize machine learning techniques to extract meaningful narratives from data and construct predictive models – especially in open-source medical contexts.</p>
  <br>
  <a href="https://www.linkedin.com/in/lucino-garcia/">LinkedIn.com/in/Lucino-Garcia</a> <br>
  <a href="https://github.com/LucinoGarcia">GitHub.com/LucinoGarcia</a> <br>
  <a href="mailto:LGarciaJr@fastmail.com">LGarciaJr@fastmail.com</a>
</div>



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


## Medical Insurance Cost Prediction

- The primary objective of this project was to employ regression models to predict the cost of medical insurance and gain valuable insights into its influencing factors.
- The dataset, sourced from Kaggle, underwent minimal data cleaning and formatting procedures to ensure its suitability for analysis.
- The selection of Linear Regression, Decision Tree, and Random Forest models was based on their adeptness in handling both categorical and continuous data types.
- Upon evaluation, the Random Forest model emerged as the top performer, exhibiting the lowest Mean Squared Error (MSE) and the highest R-squared value among the three models.
- Notably, smoking emerged as the most significant determinant of medical insurance cost, followed by BMI and age, according to the analysis.<br>

![Response_Histogram.png](/images/MedCostReg_Plot.png)

[See more of the "Medical Insurance Cost Regression" project](./Medical_Insurance_Cost.html).
<br><br><br>


<!-- Excel, Dashboard, Transportation -->
<!-- Excel, Dashboard, Coffee -->
<!-- Tableau, Dashboard, Coursera -->
<!-- SQL, YouTube -->

