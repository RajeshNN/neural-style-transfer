# Neural Style Transfer using pretrained Torchvision model with color transfer!


An implementation of the neural style in PyTorch! This notebook implements [Neural Style Transfer](https://arxiv.org/abs/1508.06576) algorithm created by Gatys et al. (2015) and [Preserving Color in Neural Artistic Style Transfer](https://arxiv.org/pdf/1606.05897.pdf) by Leon Gatys, Matthias Bethge, Aaron Hertzmann, and Eli Shechtman (2016).

The pretrained weights of VGG19 from torchvision models for classification of images were used for this implementation.
# **Examples**
## **Style Transfer**
*content image*            |  *style image*            |  *stylized content image*   |
:-------------------------:|:-------------------------:|:---------------------------:
![alt text](https://github.com/rajeshNN/neural-style-transfer-pytorch/blob/main/images/bird.jpg?raw=true)|![alt text](https://github.com/rajeshNN/neural-style-transfer-pytorch/blob/main/images/van_gogh.jpg?raw=true)|![alt text](https://github.com/rajeshNN/neural-style-transfer-pytorch/blob/main/images/van_gogh_style_transfer.jpg?raw=true)|

## **Color Preserving Algorithms**
*content image*            |  *style image*            |  *stylized content image*   |
:-------------------------:|:-------------------------:|:---------------------------:
![alt text](https://github.com/rajeshNN/neural-style-transfer-pytorch/blob/main/images/gal_gadot.jpg?raw=true)|![alt text](https://github.com/rajeshNN/neural-style-transfer-pytorch/blob/main/images/tom_n_jerry.jpg?raw=true)|![alt text](https://github.com/rajeshNN/neural-style-transfer-pytorch/blob/main/images/tom_n_jerry_style_transfer.jpg?raw=true)|

*luminance-only color transfer* | *cholesky (color histogram matching)* | *image analogies (color histogram matching)* |
:------------------------------:|:-------------------------:|:--------------------------------:
![alt text](https://github.com/rajeshNN/neural-style-transfer-pytorch/blob/main/images/tom_n_jerry_luminance_transfer.jpg?raw=true)|![alt text](https://github.com/rajeshNN/neural-style-transfer-pytorch/blob/main/images/tom_n_jerry_cholesky.jpg?raw=true)|![alt text](https://github.com/rajeshNN/neural-style-transfer-pytorch/blob/main/images/tom_n_jerry_img_analogy.jpg?raw=true)|
