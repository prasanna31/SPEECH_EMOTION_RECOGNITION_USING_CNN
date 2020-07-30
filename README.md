# SPEECH_EMOTION_RECOGNITION_USING_CNN
INTRODUCTION:
  identifing the emotion during the human to human interactions is a easy task.but while human to machin interactions it plays a key role.
  let us try to prepare a model for machines to learn the emotion recognition process.
DATASET:
  we are using a available dataset(RAVDASS) which consists of speech files in .wav format.
  this set contains the wavfiles of speeches of 24 actors in various emotions.
SPLITTING THE DATA:
  we split the data into 2 parts for testing and training and each of this dataset is categeroized into features and labels (labels are the emotions we obtain as output.)
SPECTOGRAMS:
  we convert the .wav files into spectograms before training our model.
COVOLUTIONAL NEURAL NETWORK:
  2 convolutional layers followed by a maxpooling layer are added twice.
  *activation function used is relu
  *padding is same
  *stride size is (2,2)
  now the layers are flattened to fully connected layers with activation function softmax 
  we add 
  
