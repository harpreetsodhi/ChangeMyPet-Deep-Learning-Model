# Change My Pet
<div align="center">
    <a>
        <img src="https://github.com/harpreetsodhi/ChangeMyPet_Deep_Learning_Model/blob/master/assets/logo1.png?raw=true0" width="300" height="120">
    </a>
</div>
<br />

> ChangeMyPet provides a deep learning model that is capable of replacing a real dog/cat image with a GAN(Generative adversarial network) generated image with the help of segmentation masks.

# Results:
<div align="center">
    <a>
        <img src="https://github.com/harpreetsodhi/ChangeMyPet_Deep_Learning_Model/blob/master/assets/example2.png?raw=true" />
    </a>
</div>
<hr />
<div align="center">
    <a>
        <img src="https://github.com/harpreetsodhi/ChangeMyPet_Deep_Learning_Model/blob/master/assets/example1.png?raw=true">
    </a>
</div>
<br />


# Exciting Gifs:
<div align="center">
    <a>
        <img src="https://raw.githubusercontent.com/harpreetsodhi/ChangeMyPet_Deep_Learning_Model/master/assets/gif2.gif" width="500" height="500"/>
    </a>
</div>
<br />
<div align="center">
    <a>
        <img src="https://raw.githubusercontent.com/harpreetsodhi/ChangeMyPet_Deep_Learning_Model/master/assets/gif1.gif" width="500" height="500"/>
    </a>
</div>

<br />

The project is still underway. The results are quite interesting and the model is learning to generate images in the required segment. Regularization and ensembling losses have given more accurate results but we are still exploring other techniques. Our next step is to activate Discriminator so that the images generated look more real. 


# Pretrained Weights 
The pretrained weights are converted from the tensorflow hub modules: 
- https://tfhub.dev/deepmind/biggan-128/2  
- https://tfhub.dev/deepmind/biggan-256/2 
- https://tfhub.dev/deepmind/biggan-512/2  


# References 
paper: https://arxiv.org/abs/1809.11096

https://github.com/ajbrock/BigGAN-PyTorch
