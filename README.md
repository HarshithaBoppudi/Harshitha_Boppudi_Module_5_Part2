# Harshitha_Boppudi_Module_5_Part2

Convolution: 
Convolution refers to sliding a small grid of numbers (called a kernel or filter) over an image or feature map.
-filters scan the image to detect edges, scratches, dents, stains.

Pooling: 
Pooling  is used to downsample the spatial dimensions of feature maps while retaining the most important features
-reduces image size, keeps important features, prevents overfitting.

ReLU:
ReLU (Rectified Linear Unit) is the standard activation function in CNNs because it efficiently adds necessary non-linearity to the model without causing vanishing gradient issues.
-fast, avoids vanishing gradients, introduces non-linearity.

CNN vs Feed-forward: 
Regular feed-forward networks (Dense layers) process every pixel individually as a single 1D array, ignoring the grid layout of an image. CNNs handle this better due to two key properties: Local Connectivity and Weight Sharing
-CNNs exploit spatial structure, fewer parameters, better suited for images.
