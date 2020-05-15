# Surveillance-to-identify-the-person-from-different-angles
The surveillance to identify the person from different angles is basically also known as Person Re-identification. The deep learning model detects face of the person from images and videos. If any person can be seen in the image or video in any appearance then that person can be detected using this model. The deep learning model used was Convolutional Neural Networks (CNN).

The dataset used was the images of myself and my friend Meet. I collected nearly 120 images of myself and Meet as the dataset and then I performed augmentation on it to increase the size of the dataset. Deep Learning algorithms such as Convolutional Neural Networks (CNNs) are applied on the dataset. I tried different models to check the accuracy of the model and then I got the best accuracy for one of the models. At the end I got 100% training and 97% validation accuracy and 3.2908e-04 training and 0.0209 validation loss. 

I tried different models by just changing the number of layers in the Convolutional Neural Networks.

Object Detection.ipynb file:

1.)Converts Video1 & Video2 into frames and stores into data1 and data2 folders respectively.
2.)Predicts output in each frames(data1 and data2 folders) and stores output in Predicted_data1 and Predicted_data2 folders.


Object Detection 2.ipynb file:

1.)Stores Prediction values of data1 & data2 folders into predicted1 & predicted2 arrays.
2.)Frames are Synchronized and different scenarios:

	a.)Synchronized and Predicted Video1 and Video2
	b.)Predicted Megh only
	c.)Predicted Amish only
	d.)Predicted Both only
