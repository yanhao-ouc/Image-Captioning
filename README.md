# Image-Captioning

Using Flickr8k dataset since the size is 1GB. MS-COCO is 14GB!

Used Keras with Tensorflow backend for the code. For extracting features from the image, I am using VGG-16 with the last two layers(Dense layer with 1000 hidden neurons and the Dropout layer) removed. 

The Bidirectional LSTM layer performs much better than the normal LSTM layer.

Please feel free to contribute.
