# Image Inpainting

Team Members: Aakansha B., Anika T., Sadia M.

### *Abstract*

Image inpainting is the process of filling in the missing
areas of an incomplete image. In this project we implement
a conventional neural network (CNN) based
autoencoder-decoder image inpainting technique using
structural similarity (SSIM) as metrics for training on
CIFAR-10 dataset in Python using Keras and Tensorflow
libraries. The region to be inpainted is created by the
standard image processing idea of masking. We
implemented random line and square masks and trained and
tested our model for both. Our architecture performs better
for the former. Apart from visual inspection, we used the
peak signal-to-noise ratio (PSNR) and SSIM on test images
to evaluate the effectiveness of our algorithm. Sample
PSNR and SSIM values are in the 30dB range (typical for
images) and close to +1 respectively, indicating the efficacy
of our design. 

[CNN based Image Inpainting.pdf](https://github.com/Supova/Python-Image-Inpainting/blob/main/CNN%20based%20Image%20Inpainting.pdf)
