
- In order to recognize the image of a given animal in many different angles and situations, the neural network needs to have a property called `space invariance` 
- How to do?
	1. Given you completed the `feature filter` part and you already have the `feature maps` described in [[1_Convolutional Neural Network]]
	2. You apply `Max-Pooling` (there is other types of pooling)and you obtain `Pooled Feature Map` 
- What is the beneffits?
	- Introduces `spatial invariance`
	- Preserve the features
	- Reduces features sizes (compacts), therefore reduces the number of parameters and also reduces overffiting and also reduces the noise

#### How Max-Pooling works?
1. marchall the matrix with an NxN matrix where N < _size of full matrix_ (marchal matrix can go "out of the original matrix boundaries")
2. find the max value and record only that value


#### Papers to Read:
- [ ] Evaluation of Pooling Operations in Convolutional Architectures for Object Recognition - Dominik Scherer - 2010