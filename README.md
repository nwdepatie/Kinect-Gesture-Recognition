# Kinect-Gesture-Recognition

The goal of this project is to use the Xbox Kinect to generate data to train a neural network to recognize different gestures. I'll be using TensorFlow to train and create a model to implement in a real-time recognition system. I'm using the Xbox Kinect to capture and train data because it is easy to filter out noise with it, as it's infrared depth sensor allows me to only capture a specific region a certain distance away from the camera. This means that the model I train will have to account for much less noise and will hopefully generalize better. I also just had a Kinect lying around.

### Phases of project
#### 1. Create application to easily capture and label a large quantity of data
#### 2. Create a Tensorflow neural network to train with data
#### 3. Utilize model in application to recognize gestures