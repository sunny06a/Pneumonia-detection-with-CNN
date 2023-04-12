# Pneumonia-detection-using-CNN


#Abstract 
A large number of children die due to pneumonia every year worldwide. An
estimated 1.2 million episodes of pneumonia were reported in children up to 5
years of age, of which 880,000 died in 2016.

#Dataset
The dataset was collected from the Chest X-ray pneumonia dataset. It contains
three folders named train (for training), val (for validation), and test (for testing).
Each of them has two sub-folders with label "NORMAL" and "PNEUMONIA".
https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia

#Tools
Tensorflow
Keras
sklearn
matplotlib
numpy

#Model
We have implemented a Sequential model with 7 layers (excluding output
layer). The first 5 layers are convolutional layer and the last two are dense
layers also Known as fully connected layers. Only for the first Conv layer, you
need to define the input shape. The later layers take the previous layer's output
as it's input padding is used to add extra pixel values of zero to the image.

#Result
With 5 CNN models we obtained 94% accuracy.
With 2 CNN model we obtained 90% accuracy.

