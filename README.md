# Galaxy Classification

### I was given a pickle file with around 18000 different images of galaxies. Me and 4 other peers were tasked with classifying these galaxies. There were 30 different types of galaxies (see photos below for examples). 
# 

### In order to accomplish this we tried dozens of variations of different algorythms, pretrained networks, packages. After many attempts we were able to get the RMSE down to around .114.

### To get the RMSE to .114 we tried several methods. At first we looked into Keras image recognition pretrained models such as VGG-16 and InceptionV3. This got the RMSE to .136 for VGG-16 and .12 for InceptionV3

### This was a good start; however, we felt we could still do better. We then created our own convolutional neural network with 5% dropout. This allowed us to achieve the best RSME of ~.114.
