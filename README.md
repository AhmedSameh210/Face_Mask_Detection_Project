# Mask Detection Project
This project is aimed at detecting whether or not a person is wearing a mask using deep learning models. The models used in this project are DenseNet, VGG16, ResNet, MobileNet, and EfficientNetB0.

#Dataset
The dataset used for training and testing the models is a collection of images of people with and without masks. The images were collected from various sources and were annotated manually. The dataset is split into training and testing sets with a ratio of 80:20.

#Preprocessing
Before training the models, the images were preprocessed by resizing them to a fixed size of 224x224 pixels and normalizing the pixel values. Data augmentation techniques such as random rotation, horizontal flip, and zoom were also applied to the training set to increase the diversity of the data.

#Models
The following deep learning models were used to detect masks:

1-DenseNet
2-VGG16
3-ResNet
4-MobileNet
5-EfficientNetB0
These models were chosen because they are well-known and have been shown to perform well on various computer vision tasks.

#Training
The models were trained using the training set and evaluated on the testing set. The models were trained using the Adam optimizer and the categorical cross-entropy loss function. The models were trained for 50 epochs with a batch size of 32.

#Evaluation
The models were evaluated based on their accuracy, precision, recall, and F1-score. The models were also compared based on their training time and the number of trainable parameters.



#Conclusion
The mask detection project using deep learning models showed promising results. DenseNet achieved the highest performance among all the models. The project can be extended further by collecting more data, using more advanced deep learning models, and deploying the model in real-world scenarios.
