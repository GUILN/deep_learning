
#### Opeartor

Convolution is an matrix operator, and it mathematics are based on integrals

### Characteristics

- Uses a `feature detector` or `filter` which is a smaller matrix than the input matrix, where it goes marchalling and multiplying by this matrix and the final result of this matrix multiplication is a matrix that is called `feature map` (or `convolved matrix`  or `activation map`).
- `feature map` is a kind of "compacted" input matrix, therefore:
	- You lose some information
	- It preserve the features: eg.: in an image: a feather, an cheetah's nose
	- We don't create just one feature map, we create several of feature maps (or better the network decides which feature maps to create)
#### Papers to Read 
- [ ] Gradient-Based Learning Applied to Document Recognition - Yann LeCun - 1998 (original cnn paper)
- [ ] Introduction to Convolutional Neural Networks - Jianxin Wu - 2017 (mathematics of cnn paper)