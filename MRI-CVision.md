## Disease Detection with Computer Vision
- Developed a 3D U-Net model for classifying tumors in DICOM format MRI data.
- Data was provided by the Decathlon 10 Challenge but required patching and standardization.
- A 3D U-Net model was chosen for its architecture optimized for volumetric datasets. Soft Dice was used as the loss function, and Dice Coefficient was used as the metric.
- Utilized both sensitivity and specificity as measures of model evaluation. Sensitivity and specificity varied by samples but typically exceeded 85% sensitivity and 90% specificity.
- A 3D U-Net model can definitely be utilized for cancerous tissue classification—even with samples in the hundreds. It should generalize nicely after being trained on additional datasets.

![image](/images/3_View.png)

[GitHub Repository for Disease Detection with Computer Vision](https://github.com/LucinoGarcia/MRI-Brain-Tumor-Detection)
<br><br><br>
