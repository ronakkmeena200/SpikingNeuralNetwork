# SpikingNeuralNetwork
A simple Spiking Neural Network implementation with Integrate and Fire Neurons. 
This project is an extension of B. Tech. Project under Prof Bibhudatta Sahoo (IIT Kharagpur).

## Prerequisites
The entire framework is mostly built using inbuilt python modules. 
It uses numpy for numerical optimizations.
```shell
pip install numpy
```
### Importing Dataset
To import Dataset Keras has been used.
```shell
pip install matplotlib
```


### Plotting the results (optional)
To plot the various potentials and currents, matplotlib can be used.
```shell
pip install matplotlib
```

## Structure
The network has three layers in total, all fully connected.
### Neuron
The neuron is an Integrate and Fire type neuron which is restricted to be fired only once for an input after which the network is reset. So, effectively neuron enters an infinite refractory period after it fires.
