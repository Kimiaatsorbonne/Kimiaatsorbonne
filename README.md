Theory Of CNN:
Convolutional Neural Networks (ConvNets or CNNs) are a category of Neural Net- work that is mostly used in areas such as image recognition and classification. it can be observed during the report that CNN are used as a backbone network for mentioned algorithms.
Four main operations in CovNet are which are shown:
1. Convolution
2. Activation Function (ReLU)
3. Pooling or Sub Sampling
4. Classification by Fully Connected Networks (FCN)


Convolution:
A process of applying a kernel on an original image which in mathematical aspect is Multiplication between kernel and the orginal image. The propose of convolution is to extract features from input image. By this action we decrease the image size which leads us to get to the final n unit classes.
How convolution works?
A small size matrix (Kernel, Feature detector or Filter) would be slide over a large matrix (Image). Kernel slide over the image buy the specific amount of step which is called stride. By each move the mathematical element-wise computation would be performed and the summation of each computation would be replaced in the result matrix called convolved image, activation map or feature map.
Its obvious that the images that we process is big in size or has high quantities, therefor for making this process less expensive and more easy, the image would be divided into small pieces but its not wise to divide by equal size boxes because that would not be efficient therefore by performing a selective search we extract 2000 regions from image which we call this action Region Proposal.

Activation Function (ReLU):
After each convolutions layer, an activation function is applied element-wise to intro- duce non-linearity into the network. The most commonly used activation function is the Rectified Linear Unit (ReLU), which sets negative values to zero and keeps positive values unchanged.

Pooling or Subsampling:
Spacial Pooling (Subsampling, Downsampling) reduce the dimensionality of each feature map. The operation that causes this result could be different such as: max, average, sum or . . . Similar to convolution, a spacial neighborhood would be chosen and the operation would be applied to that neighborhood and then stride.

By far all the steps that have been taken (Convolution, ReLU and Pooling), pre- pared the input data for the Neural Network. In next, these data would be filled to the Fully Connected Network.

