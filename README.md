# segmentation-projects
Various projects built off of several segmentation models

This repo consists of segmentation models I've built from scratch. Segmentation is the process where we perfectly locate a singular/multiple entities in perfect pixel-level accuracies.
check out my kaggle link attached with the respective dataset: https://www.kaggle.com/code/suhaaskarthikeyan/human-being-segmentation-unet-model
Here I've started with one file that segments human bodies from an image. It can perfectly identify the human beings in the image, and it can erase the background and any other accessories. It has been trained with over 28k images, with GPU A100 only
as you need GPUs with higher internal RAM. Training dataset has to be limited when using other GPUs. It has given us a dice loss of around 0.11, which indicates perfect segmentation.
