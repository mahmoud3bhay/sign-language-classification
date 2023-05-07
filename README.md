# sign-language-classification
This project aims to classify 26 of the English alphabet signs using a Convolutional Neural Network (CNN) model and DenseNet201 pretrained model .
The cnn model was built using the Keras library and achieved an accuracy of 97% on the test set.

# Data set 
I've used data set on kaggle 
here is the link : https://www.kaggle.com/datasets/kapillondhe/american-sign-language

# you can see cnn model archticture below : 
Model: "sequential_4"
_________________________________________________________________
 Layer (type)                Output Shape              Param #   
=================================================================
 conv2d_13 (Conv2D)          (None, 40, 40, 32)        896       
                                                                 
 max_pooling2d_12 (MaxPoolin  (None, 20, 20, 32)       0         
 g2D)                                                            
                                                                 
 conv2d_14 (Conv2D)          (None, 20, 20, 64)        18496     
                                                                 
 max_pooling2d_13 (MaxPoolin  (None, 10, 10, 64)       0         
 g2D)                                                            
                                                                 
 flatten_4 (Flatten)         (None, 6400)              0         
                                                                 
 dense_12 (Dense)            (None, 64)                409664    
                                                                 
 dense_13 (Dense)            (None, 32)                2080      
                                                                 
 dense_14 (Dense)            (None, 28)                924       
                                                                 
=================================================================
Total params: 432,060
Trainable params: 432,060
Non-trainable params: 0
_________________________________________________________________




This project demonstrates the effectiveness of using CNN models for sign language classification tasks.
The achieved accuracy of 97% on the test set shows that the model can accurately classify the English alphabet signs with high confidence.
