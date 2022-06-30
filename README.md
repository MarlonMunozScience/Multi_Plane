# Multi_Plane
Convolutional Neural Network which utilizes transfer learning to identify planes using the FGVC-Aircraft Benchmark.

This Algorithm  uses the **VGG16** Convolutional Neural Network, a NN trained on ImageNet, as a convolutional base and adds layers to retrain the Neural Network to recognize 
aircrafts using the [FGVC-Aircraft Benchmark](https://www.robots.ox.ac.uk/~vgg/data/fgvc-aircraft/#:~:text=Fine%2DGrained%20Visual%20Classification%20of,375%20KB%20%7C%20MD5%20Sum%5D.). This dataset contains 10,000 labeled images of airplanes, split into 30 classes based on Manufacturer. 

## Results
The algorithm is a multi-class output neural network capable of identifying planes based on manufacturer with a success rate of 93.62%. This is a significant increase compared to the [FGComp fine-grained recognition challenge in 2013](https://sites.google.com/site/fgcomp2013/results), which saw classifications of about 81%.

The dataset has also been reorganized so it is easier to work with in python. It will be uploaded to this repository soon.
