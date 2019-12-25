# neural-style-transfer-mobilenet

To get a custom Neural Style System on our own dataset, we will build the system using Transfer Learning.
We will use the pre-trained MobileNet as a feature extractor and then added intermediate layers from the network to represent the style and content of the image. By accessing intermediate layers of the model, you're able to describe the content and style of input images. So we will feed the input image to the Pretrained MobileNet that will extract the features from the image, once it is done then we will access the intermediate layers of the model to get the optimized output image from the content image captured the style from style image.

Reference:
https://www.tensorflow.org/tutorials/generative/style_transfer
