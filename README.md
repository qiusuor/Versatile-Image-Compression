# Versatile-Image-Compression

This repo provides the official implementation of "[iWave++](https://ieeexplore.ieee.org/document/9204799)".

Accepted by IEEE TPAMI.

Author: Haichuan Ma, Dong Liu, Ning Yan, Houqiang Li, Feng Wu

## **BibTeX**

TO DO

## **Update Notes**

2020.9.4  Upload code and models of **Lossy multi-model iWave++**.

2020.8.26 Init this repo.

## **How To Test**
0. Dependencies. We test with MIT deepo docker image.

1. Clone this github repo.

2. Place Test images. (The code now only supports images whose border length is a multiple of 16. However, it is very simple to support arbitrary boundary lengths by padding.)

3. Download models. See **model** folder.

4. python main_testRGB.py. (The path in main_testRGB.py needs to be modified. Please refer to the code.)


## **Results**

iWave++ outperforms [Joint](http://papers.nips.cc/paper/8275-joint-autoregressive-and-hierarchical-priors-for-learned-image-compression), [Variational](https://arxiv.org/abs/1802.01436), and [iWave](https://ieeexplore.ieee.org/abstract/document/8931632). For more information, please refer to the paper.

1. RGB PSNR on Kodak dataset.

![image](https://github.com/mahaichuan/Versatile-Image-Compression/blob/master/figs/Kodak.PNG)

2. RGB PSNR on Tecnick dataset.

![image](https://github.com/mahaichuan/Versatile-Image-Compression/blob/master/figs/Tecnick.PNG)
