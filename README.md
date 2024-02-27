# Convolution_Neural_Network
Convolution Neural Network for binary classification of Dogs and Cats.

1. This CNN consists of 13 2D-Convolution layers, 5-Maxpooling and 1-Fully connnected layer with ReLu Activation function.

2. All the input images are resized into 255x255 pixels dimension.

3. The model uses Binary Cross Entropy as Training Loss.

4. The structural framework of the model is as follows:

   CONV-2D
   |
   CONV-2D
   |
   MAXPOOLING(2X2, stride=2)
   |
   CONV-2D
   |
   CONV-2D
   |
    MAXPOOLING(2X2, stride=2)
   |
   CONV-2D
   |
   CONV-2D
   |
   CONV-2D
   |
    MAXPOOLING(2X2, stride=2)
   |
   CONV-2D
   |
   CONV-2D
   |
    CONV-2D
   |
    MAXPOOLING(2X2, stride=2)
   |
   CONV-2D
   |
   CONV-2D
   |
    CONV-2D
   |
    MAXPOOLING(2X2, stride=2)
   |
   FULLY-CONNECTED-LAYER(activation function = ReLu)

5. For the database, any free open source database can be used to train the model.

6. Images are to be separated as Training, Testing and Validation set.

#Requirements to run the model
--> Running on CPU will overheat the computer and take up lot of time.

--> Before running the model in the device/computer, kindly make sure to connect the platform with GPU. If visual studio codes(preferred) is used, then turn on GPU Acceleration from the settings section.

--> On charge computer with any dedicated graphic card works.
   
   
