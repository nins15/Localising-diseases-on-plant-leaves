# Localising-diseases-on-plant-leaves:Problem Review
* I have developed a system that can detect plant diseases and localization using GRADCAM.
* Obtained a highly imbalanced dataset which was then balanced using augmentation.
* This balanced datset is then fed to two multiclass CNN models for classification called ResNet and EfficientNet
* Lastly the localizations of the input image is obtained using a GRADCAM.
## About Dataset
We have used the Plantvillage for training our models. We used one plant category of apple .Within the plant village dataset there are a total of 1902 images of apple in each of the three formats called color, segmented, grayscale. And a total of 5706 images.Three diseases of apple were considered called as apple scab , cedar rust and back rot.

![alt text](https://github.com/nins15/Localising-diseases-on-plant-leaves/blob/master/imagedistribution.png "distribution")
