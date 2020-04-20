# MATH-7243-Project-

It has always been a challenge for brain surgeons to pinpoint the ventricle area within a patient’s head.
Surgeons so far have been operating by experience or educated guess when trying to locate it. To
maximize the accuracy in locating the ventricle area for operation, we introduce machine learning. In this
report, we discuss how we utilized the U-net structure convolution neural network to segment the
ventricle area from a 3-D MRI scan. Throughout the training process, data augmentation is also utilized to
resolve the shortage of samples, including downsampling and lateral flips. Our model consists of 1.4
million parameters and numerous convolution, max pooling and upsampling layers, and our convolution
neural network provides a high prediction accuracy of the ventricle area from an input of an MRI scan.

MRI Image Segmentation Dataset
# OASIS 1 DATA : https://www.oasis-brains.org/#data

Different files:<br>
model -  contains 3D CNN architecture<br>
Data Augmentation -  Handeling imbalances in data<br>
Visualization_weights - Contains sample models trained and visualization of their weights<br>
Accuracy test- Loaded completely new samples and tested our model on it<br>
 
Report- Project report 

