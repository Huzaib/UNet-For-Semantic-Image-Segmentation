# UNet For Semantic Image Segmentation

## UNet
The UNET was developed by Olaf Ronneberger et al. for Bio Medical Image Segmentation. The architecture contains two paths. First path is the contraction path (also called as the encoder) which is used to capture the context in the image. The encoder is just a traditional stack of convolutional and max pooling layers. The second path is the symmetric expanding path (also called as the decoder) which is used to enable precise localization using transposed convolutions. Thus it is an end-to-end fully convolutional network (FCN), i.e. it only contains Convolutional layers and does not contain any Dense layer because of which it can accept image of any size.

## Semantic Segmentation
Semantic segmentation refers to the process of linking each pixel in an image to a class label. These labels could include a person, car, flower, piece of furniture, etc., just to mention a few. We can think of semantic segmentation as image classification at a pixel level. For example, in an image that has many cars, segmentation will label all the objects as car objects.


## Here is a link to my trained model for reproducing the same results: [Trained Model](https://drive.google.com/file/d/1lLKUoaaLOkJ7zo3H7XVV0v6gUbqq8IJt/view?usp=sharing)


# Encoder Architecture
![Encoder Architecture](https://github.com/Huzaib/UNet-For-Semantic-Image-Segmentation/blob/master/Architecture%20Plots/unet_encoder.png)


# Decoder Architecture
![Decoder Architecture](https://github.com/Huzaib/UNet-For-Semantic-Image-Segmentation/blob/master/Architecture%20Plots/unet_decoder.png)


# Overall Architecture
![Overall Architecture](https://github.com/Huzaib/UNet-For-Semantic-Image-Segmentation/blob/master/Architecture%20Plots/unet.png)


# Training And Validation Loss
![Loss Graph](https://github.com/Huzaib/UNet-For-Semantic-Image-Segmentation/blob/master/Loss%20Plot/loss.png)


# Final Results
![Output Example 2](https://github.com/Huzaib/UNet-For-Semantic-Image-Segmentation/blob/master/Output%20Images/output_example_2.png)
![Output Example 3](https://github.com/Huzaib/UNet-For-Semantic-Image-Segmentation/blob/master/Output%20Images/output_example_3.png)
![Output Example 1](https://github.com/Huzaib/UNet-For-Semantic-Image-Segmentation/blob/master/Output%20Images/output_example_1.png)
![Output Example 4](https://github.com/Huzaib/UNet-For-Semantic-Image-Segmentation/blob/master/Output%20Images/output_example_4.png)
![Output Example 5](https://github.com/Huzaib/UNet-For-Semantic-Image-Segmentation/blob/master/Output%20Images/output_example_5.png)



# References
- [U-Net: Convolutional Networks for Biomedical Image Segmentation](https://arxiv.org/abs/1505.04597)
- [Understanding Semantic Segmentation with UNET](https://towardsdatascience.com/understanding-semantic-segmentation-with-unet-6be4f42d4b47)
- [U-Net for segmenting seismic images with keras](https://www.depends-on-the-definition.com/unet-keras-segmenting-images/)
- [UNet — Line by Line Explanation](https://towardsdatascience.com/unet-line-by-line-explanation-9b191c76baf5)
- [Semantic Segmentation with Deep Learning](https://towardsdatascience.com/semantic-segmentation-with-deep-learning-a-guide-and-code-e52fc8958823)
