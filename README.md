# Gender Classification with CNN
Classification model for Gender identification (Only Male and Female classes)

## About the dataset
The data set is of cropped images of male and female . It is split into training and validation directory. Training contains ~23,000 images of each class and validation directory contains ~5,500 images of each class.

## Example images from the dataset
<img src="https://github.com/Siddharth-ct/Gender-Classification-with-CNN/blob/main/files/063581.jpg.jpg" width="180px"></img> 
<img src="https://github.com/Siddharth-ct/Gender-Classification-with-CNN/blob/main/files/063594.jpg.jpg" width="180px"></img> 
<img src="https://github.com/Siddharth-ct/Gender-Classification-with-CNN/blob/main/files/063595.jpg.jpg" width="180px"></img> 

<img src="https://github.com/Siddharth-ct/Gender-Classification-with-CNN/blob/main/files/113024.jpg.jpg" width="180px"></img> 
<img src="https://github.com/Siddharth-ct/Gender-Classification-with-CNN/blob/main/files/113027.jpg.jpg" width="180px"></img> 
<img src="https://github.com/Siddharth-ct/Gender-Classification-with-CNN/blob/main/files/113036.jpg.jpg" width="180px"></img> 



## Implementation accuracy
--> Data Augmentation Implemented

<b>Train set accuracy:</b> ~94%<br/>
<b>Validation set accuracy :</b> 93.05%<br/>

The accuracy is quite good. The model was trained for 30 epochs. With a bit of tweaking of models layers, dropouts, increasing the number of filters etc and training the model for 100 epochs or more will result in very high accuracy.

## The following additional plots and charts were made to understand the model beter.
<b>Loss vs Epochs</b>

<img src="https://github.com/Siddharth-ct/Gender-Classification-with-CNN/blob/main/files/Screenshot%20from%202022-06-27%2005-26-31.png">


<b>Binary accuracy vs Epochs</b>

<img src="https://github.com/Siddharth-ct/Gender-Classification-with-CNN/blob/main/files/Screenshot%20from%202022-06-27%2005-26-29.png">
