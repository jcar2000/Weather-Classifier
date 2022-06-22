# Basic Weather Classifier

### **Summary**

A basic weather classifier built in a python notebook.

Uses a customized AlexNet cnn model and a relatively small dataset of ~1000 images to predict images of a natural landscape/the sky and classify them into one of 4 potential classes.

These classes are Cloudy, Rain, Shine and Sunrise and come frome the following dataset:

**Multi-class Weather Dataset for Image Classification -** https://data.mendeley.com/datasets/4drtyfjtfy/1

------------

### **Experimental Results**

The model was able to provide a training and validation accuracy of 0.9852 and 0.9427 respectively with a loss of 0.0438 and 0.2583 respectively after 500 epochs of training. 

![accuracy](https://user-images.githubusercontent.com/62224239/175078761-b0435669-5637-4d13-8ca7-deebb2949a94.jpg)
![loss](https://user-images.githubusercontent.com/62224239/175078561-e3e5b9e7-54c9-4908-bd87-294061c7fad9.jpg)

Examples of test predictions on images taken from google (not contained in the dataset):

![predicts](https://user-images.githubusercontent.com/62224239/175078863-fd1fc6c5-bb6e-4368-a9d0-3c6021af7bbd.png)
