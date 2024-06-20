# Neural_Style_Transfer
NST is the technique of blending style from one image into another image keeping its content intact. The only change is the style configurations of the image to give an artistic touch to your image. The content image describes the layout or the sketch and the Style is the painting or the colors. It is an application related to image processing techniques and Deep Convolutional Neural Networks. The Keras library contains a pretrained VGG19 model that can be imported. We define two Keras variables to hold the content image and style image and a placeholder that will
contain the generated combined image. The input tensor to the VGG19 model 
is a concatenation of the three images.
![image](https://github.com/vedantikale/Neural_Style_Transfer/assets/122674631/cbc79a73-0159-41c9-ae5a-3faa376cf75b)
