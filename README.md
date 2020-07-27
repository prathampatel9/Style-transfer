# Style-transfer
Style transfer is a fun technique in deep learning. Style Transfer refers to a class of software algorithms that manipulate digital images, or videos, to adopt the appearance or visual style of another image. Style Transfer is a process in which we strive to modify the style of an image while preserving its content. Given an input image and a style image, we can compute an output image with the original content but a new style.
I have provided with two methods the first code provided in file "Style transfer.pynb" has been created using pre trained VGG-16 neural network.Technology Used
We load a pre-trained Convolutional Neural Network (VGG16 (classification error rate of only 7.0%)). It usually refers to a deep convolutional network for object recognition developed and trained by Oxford's renowned Visual Geometry Group (VGG), which achieved very good performance on the ImageNet dataset.
Knowing that we can distinguish layers that are responsible for the style (basic shapes, colors etc.) and the ones responsible for the content (image-specific features), we can separate the layers to independently work on the content and style. Then we set our task as an optimization problem where we are going to minimize: -
•	Content loss (distance between the input and output images - we strive to preserve the content).
•	Style loss (distance between the style and output images - we strive to apply a new style).
•	Total variation loss (regularization - spatial smoothness to denoise the output image).
 TensorFlow: -It is an open source artificial intelligence library, using data flow graphs to build models. It allows developers to create large-scale neural networks with many layers. TensorFlow is mainly used for: Classification, Perception, Understanding, Discovering, Prediction and Creation.

Style_transfer_VGG19 is my latest code in which i used a pre trained VGG 19 neural networks.
