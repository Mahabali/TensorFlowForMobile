# TensorFlowForMobile

This is a simple tutorial for implementing machine learning with custom model in mobile apps. This tutorial consists of 3 parts


## Repos
  Simple TensorFlow Model for computing y= 2x+1. There are 3 repos
1. [Tensorflow model](https://github.com/Mahabali/TensorFlowForMobile)
2. [TensorflowLite Model for Android](https://github.com/Mahabali/TFLiteAndroidSample). 
3. [CoreML model for iOS (using CoreML tools)](https://github.com/Mahabali/CoreMLSampleiOS)

I could have used tensorflow lite for iOS. I implemented CoreML because, its easier with documentation and debugging. CoreML also supports on device machine learning. TFLite in iOS does not support on device machine learning.

I have used 'Nadam' optimizer with Mean absolute error regression loss. Feel free to play with different optimizer.

## How to use

1. Go to colab.google.com
2. Open the jupyter notebook(ipynb) in this repo
3. Click 'Connect' and wait till you get a free connection to google compute python backend
4. Run the code

 I have added comments in the jupyter notebook which are self explanatory. 
 
 When you successfully run all the code, you get the following items in files
 
1. SampleModel.h5 - Tensor flow model which can be used later
2. SampleTFLiteModel.tflite - TFLite Model for Android
3. SampleMLModel.mlmodel - CoreML Model for iOS 

### iOS Screenshot
![Screenshot](https://github.com/Mahabali/CoreMLSampleiOS/blob/main/Screenshot.png)

### Android Screenshot
![Screenshot](https://github.com/Mahabali/TFLiteAndroidSample/blob/main/Screenshot.png)
