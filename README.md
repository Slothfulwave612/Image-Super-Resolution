# Image-Super-Resolution

### Overview

The goal of this project is to recover a high resolution image from a low resolution input. In order to accomplish this goal, we will be deploying the super-resolution convolutional neural network (SRCNN) using Keras. This network was published in the paper, Image Super-Resolution Using Deep Convolutional Networks by Chao Dong, et al. in 2014.

The research paper is attached in the GitHub Repository itself.

Single image super-resolution, which aims at recovering a high-resolution image from a single low resolution image, is a classical problem in computer vision, and the researchers named the proposed model Super-Resolution Convolutional Neural Network. (SRCNN)

The SRCNN is a deep convolutional neural network that learns end-toend mapping of resolution to high resolution images. As a result, we can use it to improve the image quality of low resolution images.

In here, we present a fully convolutional neural network for image super-resolution. The network directly learns an end-to-end mapping between low and high-resolution images, with little pre/postprocessing beyond the optimization.

### Directories/Files:

1. *py_code.ipynb*: Jupyter notebook where the code is present.

2. *py_code_images*: Images used inside the jupyter notebook.

3. *source*: High resolution images that were used in SRCNN paper.

4. *Images*: Low resolution images generated from High resolution images.

5. *output*: Reconstructed images using SRCNN.

6. *3051crop_weight_200.h5*: pre-trained weights.

### SRCNN Output:

![comic](https://user-images.githubusercontent.com/33928040/84243013-3cc37600-ab1f-11ea-8e4a-4f84a6903e2f.png)
