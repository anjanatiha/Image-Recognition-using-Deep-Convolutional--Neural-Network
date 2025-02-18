## Image Recognition using Deep Convolutional Neural Network and Retraining Pretrained Models 	                                           
<pre>
Domain                 : Computer Vision, Machine Learning
Sub-Domain             : Deep Learning, Image Recognition
Techniques             : Deep Convolutional Neural Network, ImageNet, Inception
Application            : Image Recognition, Image Classification
</pre>

### Description
<pre>
1. Developed image recognition tool using Deep Convolutional Neural Network built from scratch with Keras Sequential model and, pretrained model “Inception” separately for fine-tuning with new class labels.
2. Trained on multiple datasets:
      1. Flower dataset (Testing Accuracy - 89.67%, 5 species, 4327 images).
      2. 10 Monkey species (Validation Accuracy – 97.06%, 553MB).
      3. Dog Breed dataset (Testing Accuracy - 71.61%%, 120 class, 10222 images).
</pre>

#### Flower Dataset:
<pre>
Dataset Name     : Flower Dataset
Dataset Link     : <a href=https://www.kaggle.com/alxmamaev/flowers-recognition/home>Flowers Recognition</a>
</pre>

<pre>
<b>Dataset Details</b>
Dataset Name            : Flower Dataset
Number of Class         : 5
Number/Size of Images   : Total      : 4327 (228 Megabyte  (MB))
                          Training   : 3031 (158 Megabyte  (MB))
                          Validation : 866  (51.8 Megabyte (MB))
                          Testing    : 426  (26.6 Megabyte (MB)) 

<b>Model Parameters</b>
Machine Learning Library: Keras
Base Model              : InceptionV3
Optimizers              : Adam
Loss Function           : categorical_crossentropy

<b>Training Parameters</b>
Batch Size              : 64
Number of Epochs        : 50
Training Time           : 40 min

<b>Output (Prediction/ Recognition / Classification Metrics)</b>
<b>Validation</b>
Accuracy                : 90%

<b>Testing</b>
Accuracy                : 89.67%
Loss                    : 0.36  
Precision               : 90.45%
Recall                  : 89.67%

</pre>

<!--
Best Model : data\output\models\14-val_acc-0.90-val_loss-0.39.hdf5
Accuracy                : 89.67%
Loss                    : 0.36  
Precision               : 90.45%
Recall                  : 89.67%
-->

##### Sample Output: 
<kbd>
<img src=https://github.com/anjanatiha/Image-Recognition-using-Deep-Convolutional-Neural-Network/blob/master/Flowers%20Recognition/demo/sample/sample.png>
</kbd>

<kbd>
<a href=https://github.com/anjanatiha/Image-Recognition-using-Deep-Convolutional-Neural-Network/blob/master/Flowers%20Recognition/demo/images/result.png>See More Images</a>
</kbd>

##### Confusion Matrix: 
<kbd>
<img src=https://github.com/anjanatiha/Image-Recognition-using-Deep-Convolutional-Neural-Network/blob/master/Flowers%20Recognition/demo/report/CM.png alt="Confusion Matrix" width=600px height=400px>
</kbd>

#### Monkey Dataset:
<pre>
Dataset Name            : 10 Monkey Species
Dataset Link            : <a href=https://www.kaggle.com/slothkong/10-monkey-species>10 Monkey Species</a>
</pre>

<pre>
<b>Dataset Details</b>
Dataset Name            : Monkey Dataset
Number of Class         : 10
Number/Size of Images   : Total      : 1370 (553 Megabyte (MB))
                          Training   : 1098 (434 Megabyte (MB))
                          Validation : 272  (119 Megabyte (MB))
                          Testing    : 0    (0   Megabyte (MB))

<b>Model Parameters</b>
Machine Learning Library: Keras
Base Model              : InceptionV3
Optimizers              : Adam
Loss Function           : categorical_crossentropy

<b>Training Parameters</b>
Batch Size              : 64
Number of Epochs        : 50
Training Time           : 40 min

<b>Output (Prediction/ Recognition / Classification Metrics)</b>
<b>Validation</b>
Accuracy                : 97.0%
Loss                    : 0.11

<!--
<b>Testing</b>
Accuracy                : 
Loss                    : 
Precision               : 
Recall                  : 
Specificity             : -->
</pre>

<!--
Best Model Path (Accuracy): 27-val_acc-0.97-val_loss-0.11.hdf5
Best Test Accuracy: 97.0%
Best Test Loss: 0.11
-->
##### Sample Output: 
<kbd>
<img src=https://github.com/anjanatiha/Image-Recognition-using-Deep-Convolutional-Neural-Network/blob/master/Monkey%20Recognition/demo/sample/sample.png>
</kbd>

<kbd>
<a href=https://github.com/anjanatiha/Image-Recognition-using-Deep-Convolutional-Neural-Network/blob/master/Monkey%20Recognition/demo/images/result.png>See More Images</a>
</kbd>

#### Dog Dataset:
<pre>
Dataset Name     : Dog Breed Identification
Dataset Link     : <a href=https://www.kaggle.com/c/dog-breed-identification>Dog Breed Identification</a>
</pre>

<pre>
<b>Dataset Details</b>
Dataset Name            : Dog Breed Identification Dataset
Number of Class         : 120
Number/Size of Images   : Total      : 10222 (344  Megabyte (MB))
                          Training   : 7221  (239  Megabyte (MB))
                          Validation : 2043  (71.1 Megabyte (MB))
                          Testing    : 958   (34.3 Megabyte (MB))

<b>Model Parameters</b>
Machine Learning Library: Keras
Base Model              : InceptionV3
Optimizers              : Adam
Loss Function           : categorical_crossentropy

<b>Training Parameters</b>
Batch Size              : 64
Number of Epochs        : 50
Training Time           : 

<b>Output (Prediction/ Recognition / Classification Metrics)</b>
<b>Validation</b>
Accuracy                : 76.41%

<b>Testing</b>
Accuracy                : 71.61%
Loss                    : 1.59
<!--
Precision               : 
Recall                  : 
Specificity             : -->
</pre>

<!--
----------------- Summary of Model Performance on Test Dataset -----------------
Best Model Path (Accuracy): data\output\models\\28-val_acc-0.66-val_loss-1.80.hdf5
Best Test Accuracy: 71.61%
Best Test Loss: 1.59
----------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------
Best Model Path (Loss): data\output\models\\12-val_acc-0.67-val_loss-1.53.hdf5
Best Test Accuracy: 68.16%
Best Test Loss: 1.45
-->
##### Sample Output: 
<kbd>
<img src=https://github.com/anjanatiha/Image-Recognition-using-Deep-Convolutional-Neural-Network/blob/master/Dog%20Breed%20Identification/demo/sample/sample.png>
</kbd>

<kbd>
<a href=https://github.com/anjanatiha/Image-Recognition-using-Deep-Convolutional-Neural-Network/blob/master/Dog%20Breed%20Identification/demo/images/result.png>See More Images</a>
</kbd>

#### Tools / Libraries
<pre>
Languages               : Python
Tools/IDE               : Anaconda
Libraries               : Keras, TensorFlow, Inception, ImageNet
</pre>

#### Dates
<pre>
Duration                : September 18 - September 19
Current Version         : v1.0.0.10
Last Update             : 09.16.2019
</pre>
