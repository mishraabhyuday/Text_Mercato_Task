# find the textual description of a fashion image through its url
This includes 2  assignments ,which aim to find the textual description of a fashion image through its url
(NOTE:This is an image from another code,just for illustration purpose)
![Image_Cap](https://user-images.githubusercontent.com/52039001/103449121-a1b40880-4cc9-11eb-807c-b256b64cf9c6.PNG)

Assgn1:
In  this ,we input a set of images and their text descriptions and use ResNet(CNN) alongwith LSTM(RNN) to prepare our model
A sequential model is built using Keras and is trained in 500 image dataset with 100 Epochs.
The average training accuracy is about 45% .
The final prediction is shown in the below lines of code and is tested over an image test_img.jpg downloaded from internet and later on random 5 images from the dataset.

Assgn2:
In this, we input images and expect to get the Neckline,Material,etc. 
The CNN model is very less accurate due to less dataset available,hence I used the VGG19 model and trained the model on the given dataset alongwith using augmentation
technique to optimize my algorithm.
Hence ,This is the soln.
