# Image-Style-Transfer-based-on-VGG16

In this project, a classical deep learning algorithm, convolutional neutral network (CNN), was implemented to realize style transfer of image. A network of VGG16 was created and a model was trained for the image classification. 

## Get started
### Set up
Stages in VGG16 include convolutional layer, activation layer, pooling layer, fully connected layer and forward and backward propagation. Since the number of layers of VGG16 is large and the computation speed of our equipment is not good enough, the training time needs to last for weeks and it is too long for us. A pretrained model of VGG16 was used and I extracted the parameters of layers from the model directly. 

### Modeling and Image Style Transfer
By using the optimized parameters and the input images, a result image could be created combining the input content image and input style image. Parameters like layer combination and coefficients of loss were studied and compared in terms of the effect of result images.


