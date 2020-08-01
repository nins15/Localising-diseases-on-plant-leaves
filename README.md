# Localising-diseases-on-plant-leaves:Problem Review
* I have developed a system that can detect plant diseases and localization using GRADCAM.
* Obtained a highly imbalanced dataset which was then balanced using augmentation.
* This balanced datset is then fed to two multiclass CNN models for classification called ResNet and EfficientNet
* Lastly the localizations of the input image is obtained using a GRADCAM.
## About Dataset
We have used the Plantvillage for training our models. We used one plant category of apple .Within the plant village dataset there are a total of 1902 images of apple in each of the three formats called color, segmented, grayscale. And a total of 5706 images.Three diseases of apple were considered called as apple scab , cedar rust and back rot.

![alt text](https://github.com/nins15/Localising-diseases-on-plant-leaves/blob/master/imagedistribution.png "distribution")
## Image augmentation
As the images are classes are highly imbalanced we have used image augmentation to balance them. For augmentation we have used three techniques,they are:
* Random Rotation
* Random Noise
* Horizontal Flip
## Building classification models

We have used transfer learning and used two CNN models they are:

1)ResNet

![alt text](https://github.com/nins15/Localising-diseases-on-plant-leaves/blob/master/Resnetaccuracy.png "resnetacc")

![alt text](https://github.com/nins15/Localising-diseases-on-plant-leaves/blob/master/Resnetloss.png "resnetloss")


2)EfficientNet

![alt text](https://github.com/nins15/Localising-diseases-on-plant-leaves/blob/master/Efficientnetaccuracy.png "efficientnetacc")

![alt text](https://github.com/nins15/Localising-diseases-on-plant-leaves/blob/master/Efficientnetloss.png "efficientnetloss")
