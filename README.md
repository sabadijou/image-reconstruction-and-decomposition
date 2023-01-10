# Image reconstruction and decomposition
A simple repository for image reconstruction and decomposition

## Task 1 : Image reconstruction
A simple and lightweight (2.46 M parameters and 1.87 GMac computational complexity) convolutional neural network is used to reconstruct gray scale images. The network benefits from a convolutional encoder that strides the gray images to latent space using 5 Downsampler Modules. Also, the network uses a convolutional decoder created by 5 Upsampler layers to reconstruct the input.

<html>
<p align="center">
<img src="https://raw.githubusercontent.com/sabadijou/images/main/Fig1.jpg">
    <br>
<em>Network Architecture</em>
</p>
</html>

## Task 2 : Image decomposition
As shown in the following Figure, I added two extra heads to the pretrained U-Net and then finetuned the whole network. The Crossroad L2 Loss function has been employed for training.

<html>
<p align="center">
<img src="https://raw.githubusercontent.com/sabadijou/images/main/Fig4.jpg">
    <br>
<em>Network Architecture</em>
</p>
</html>
