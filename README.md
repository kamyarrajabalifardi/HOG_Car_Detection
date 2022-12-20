# Car Detection
In this problem we use ***HOG*** feature of image and train a ***SVM*** binary classifier for vehicle detection. Next, we use gaussian pyramid of image and sliding window to detect probable cars in the image. Finally, we make use of ***non maximum suppression*** and ***mean shift technique*** to merge boxes near each other. 

The confusion matrix and ROC curve of SVM classifier is shown below:
<p align="center">
<img width = "700" src="https://user-images.githubusercontent.com/46090276/208689192-c175d7ed-b7b6-4715-87c6-a2249aec393b.JPG" alt="Corresponding_Points">
</p>

Here is a result from my code:
<p align="center">
<img width = "500" src="https://user-images.githubusercontent.com/46090276/195152219-3381b17d-8ee8-44d1-a835-cd2f441b943f.jpg" alt="Corresponding_Points">
</p>
