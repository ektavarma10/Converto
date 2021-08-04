# Converto
## Hand Writing Recognition Using Convolution Neural Network 

This notebook is the implementation of Machine Learning model to classify writers based on their handwritings . Dataset used is IAM top 50 Dataset (where only 50 handwriting styles are considered).Here is the [Link](https://drive.google.com/drive/folders/1L7VNbUVmzFAq2HtNt31RwW_OosYjubHQ?usp=sharing) for the dataset .

I have built this model using Keras and Tensorflow . It is language independent as we are not considering letters in the classification , but patches of image 113X113 pixels are extracted from data and fit into the model for learning .

### About Model :

Optimizer : Adam 

Convolution Layers : 3 

Pooling: Max Pooling 

Activation Functions Used : relu , softmax

For more details regarding model structure please refer to the [this](https://github.com/missione/Converto-/blob/main/ConvertoModelLayerStructure.txt) file .

This model gives 81% accuracy on test data for 9 epochs.
