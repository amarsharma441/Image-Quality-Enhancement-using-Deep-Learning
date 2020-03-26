# Image Deblurring and Quality Enhancement using Deep Convolutional Generative Adversarial Network (DCGAN)
* Implemented conditional DCGAN to improve the quality of blurry images.
* Used U-Net architecture to encode high level features and employed transpose convolution in decoding layers to generate deblurred(sharp) images.
* Used 10 types of blurring kernel with varying filter shapes, to build a dataset of 1,30,000
blurry images with their ground truth values.
* Achieved better results than the existing state of the art models by combining -
Perceptual, Wasserstein, Binary cross entropy and L1 loss.
* Obtained average PSNR and SSIM score of 68.17 and 0.9 respectively on a test sample of
10,000 images.

# RESULTS


![](https://github.com/amarsharma441/Image-Deblurring-Using-DCGAN/blob/master/Results/res.png)
