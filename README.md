# BigGAN Generators combined with Image Segmentation Model in Pytorch 
A Pytorch implementation for replacing a dog/cat image with a GAN(Generative adversarial networks) generated image. The outline(segment mask) of the dog/cat is created using an Image segmentation model.

# Results 
|![alt text](./assets/p1.png)|
|:--:|
|*class 156 (512 x 512)*|
|![alt text](./assets/p2.png)|
|*class 11 (512 x 512)*|
|![alt text](./assets/p3.png)|
|*class 821 (512 x 512)*|


# Pretrained Weights 
The pretrained weights are converted from the tensorflow hub modules: 
- https://tfhub.dev/deepmind/biggan-128/2  
- https://tfhub.dev/deepmind/biggan-256/2 
- https://tfhub.dev/deepmind/biggan-512/2  


# References 
paper: https://arxiv.org/abs/1809.11096

https://github.com/ajbrock/BigGAN-PyTorch
