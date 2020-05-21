# Neural Style Transfer

This is a style transfer implementation for this [paper](https://arxiv.org/pdf/1508.06576v2.pdf) proposed by Leon A. Gatys, Alexander S. Ecker, and Matthias Bethge.

Utilizing the feature layers of the pre-trained VGG19 model, it would transform the base input image into a new image with input content and style. The model would try minimize a weighted content-style loss using standard backpropagation.

* `cnn_art_vgg19.ipynb`: this iPynb file contains all the code.

* `/img_data`: this folder contains several *cropped* photos and art works for this project.

* `/plots`: this folder stores transformed photos.

* `/log`: this folder contains txt files of training logs.