# fathom_pre
Deep neural networks are developping fast. During these years, a lot of ideas have been put forward. Such as AlexNet, NIN(network in network), ResNet(Residual Network), Inception net, RNN(Recurrent Neural Network), LSTM(long short term memory network), etc. And all these have been used in all domains of human life. My work was to study the usage of these neural network within the embedded system Fathom USB. The labouratory U2IS of ENSTA-Paristech, as a partner of Movidius company, has an evalution prototype of Fathom USB stick, which is an embedded calculation system based on Manycore Myriad-2 processor. It is equipped with a pseudo-compilation for neural network, which can transform the deep network of the framework Caffe or TensorFlow into an optimized binary code that can be processed by Myriad-2 [13]. First object was to test the stick for the recognition of images, type Cifar-10 [11]. In the second part, the object was to design a network compatible with Fathom in practical problem, the recognition of plankton in projet H2020 BRIDGES EcoTaxa [10], which offers a rich data base of non-uniform taxonomic tree.
