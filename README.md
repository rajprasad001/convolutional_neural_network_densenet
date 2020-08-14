# Convolutional Neural Network Densenet

Densely Connected Convolutional Networks are special architecture proposed by Gao Huang and team.

The network consist of blocks that contains convolution layers. The input of a layer is concatenated to all further layers
in the block. This is called skip connections. This architecture ensures maximum information flow between layers in the 
network.

The size of the image reduces after every block. This is because after every block the the convolution layers undergoes transition
layer which comprises a convolution layer and maxpooling with stride 2.

The benefits of DenseNets is that it offers high performance with less number of parameters.

