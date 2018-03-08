# Saliency-Map
Convolutional Neural Networks, known as CNN, are widely used for computer vision tasks, such as image classification, object detection, and so on. However, a big debate about CNN, or the entire deep learning in the society right now is that people cannot understand what happens inside the "black box." Therefore, one paper was published as a way to respond that debate. The paper is from Karen Simonyan, Andrea Vedaldi, and Andrew Zisserman. "Deep Inside Convolutional Networks: Visualising Image Classification Models and Saliency Maps", ICLR Workshop 2014. 

This paper explains in image classification task, which part of image is important for accomplishing the task. It generates a saliency map according to each pictures.

Therefore, this project is an PyTorch implementation of the paper. We use both SqueezeNet1_1 and VGG11 on ImageNet.

For illustrating purposes, we only show case of 5 images and their saliency maps.
