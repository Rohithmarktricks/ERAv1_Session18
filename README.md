# ERAv1_Session18


As a part of this Assignment, we shall be developing a ```UNET``` and a ```VAE``` models.

Task:
```
Task 1:  To train your own UNet from scratch, you can use the dataset and strategy provided in this link. 

However, Training has to be done using 4 strategies:

MaxPooling +Transposed Convolution +BCE
MaxPooling +Transposed Convolution +Dice Loss
StrConv +Transposed Convolution +BCE
StrConv +Upsampling +Dice Loss

Task 2: Design a variation of a VAE that:

takes in two inputs:
    1. an MNIST image, and
    2. its label (one hot encoded vector sent through an embedding layer)
        Training as you would train a VAE

    3. Now randomly send an MNIST image, but with a wrong label. Do this 25 times, and share what the VAE makes (25 images stacked in 1 image)!
    4. Now do this for CIFAR10 and share 25 images (1 stacked image)!
```


Task1:
Link to the Jupyter Notebook: 
Oxford PET IIIT Dataset was used to train the UNet model with 4 strategies.
Plots of the 4 training strategies are as follows




Task 2:
Two Variational autoencoder networks have been trained for the task.

```For MNIST dataset```
A simple VAE with flatten layer and Linear layers was used. Trained for over 30 epochs, and the results are as follows:
