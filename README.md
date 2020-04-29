# generative-style-transfer
This repository contains recently successful style transfer algorithms implemented by me at the educational center "Sirius". Algorithms:
## - Neural style transfer. 
Classical implementation using pretrained VGG19 to calculate content and style tensors.

![](https://sun9-62.userapi.com/c858328/v858328638/1c6fb2/l8EIxwJ5Fkw.jpg)

## GAN
Classical implementation training two networks simultaneously in order to get generator that knows the distribution of train data and can reproduce it from random noise

![](https://sun9-6.userapi.com/c858328/v858328638/1c7033/pdllMeHy3tk.jpg)![](https://sun9-33.userapi.com/c858328/v858328638/1c703a/9jOmROx4ymA.jpg)
![](https://sun9-2.userapi.com/c858328/v858328638/1c7041/v_hvy-fGuiU.jpg)

## - pix2pix
Implemented in keras using GAN architecture on shoes dataset.

 ![](https://sun9-51.userapi.com/c858328/v858328638/1c6fbc/3-Wgspo8UO0.jpg)

## CycleGAN

So, we have two generators learning functions mapping from two domains X -> Y and X <- Y (aka from horses two zebras and vice versa). We used them to teach neural networks make black and white comics look bright. Not colorize them but make them look like they were painted by instagram artist.
![](https://sun9-19.userapi.com/c858328/v858328638/1c6fc4/BzqXZTh-bBo.jpg)
