# ConvolutionNeuralNetwork
It is a branch of DeepLearning used to do images recognition, images classifications. Objects detections, recognition faces etc. Cnn consist of some layers to train a image or object.

They are....

# ReLu Layer
ReLU stands for Rectified Linear Unit for a non-linear operation. The output is ƒ(x) = max(0,x).
ReLU’s purpose is to introduce non-linearity in our Cnn Since, the real world data would want our Cnn to learn would be non-negative linear values.There are other non linear functions such as tanh or sigmoid can also be used instead of ReLU. Most of the data scientists uses ReLU since performance wise ReLU is better than other two.

# Pooling Layer
Pooling layers section would reduce the number of parameters when the images are too large. Spatial pooling also called subsampling or downsampling which reduces the dimensionality of each map but retains the important information. 
# Maxpooling
Max pooling take the largest element from the rectified feature map. Taking the largest element could also take the average pooling. Sum of all elements in the feature map call as sum pooling.

# Flattening
Flattening is converting the data into a 1-dimensional array for inputting it to the next layer. We flatten the output of the convolutional layers to create a single long feature vector. And it is connected to the final classification model, which is called a fully-connected layer.

# Fully-Connected Layer
we flattened our matrix into vector and feed it into a fully connected layer like neural network.
