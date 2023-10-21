# Article - 2023-09-28

- [udemy course](https://www.udemy.com/course/deeplearning/learn/lecture/6820144#overview)
- **Tags:** 

**Other Resources:**
- [Super Data Science RNN](https://www.superdatascience.com/blogs/the-ultimate-guide-to-recurrent-neural-networks-rnn)
## Main Information

| Article Name | Source | Subject | Model | Metric | Dataset |
| ------------ | ------ | ------- | ----- | ------ | ------- |
|              |        |         |       |        |         |

## 1. The idea behind recurrent neural networks

- ANN Weights represents long term memory
- RNN are like short term memory, where we can add a feedback loop to a neuron in a hidden layer, which can "remember" information through the "epochs"


**RNN - Timeline Representation:**

![[rnn_time_representation]]
**RNN - Old school representation:**

![[rnn_oldschool_representation]]
## 2. The vanishing gradient problem

- As represented in the images above, as you now introduce another factor to multiply (the recurrent layer), now to more you multiply the lower the value will get.
- When you back propagate your gradient will become less
- The lower the gradient is the more difficult to the network to update the weights with back propagation 
- The lower the gradient the slowest is going to update the weights (*Wrec*)

$$W_{rec} \approx small \iff \text{  Vanishing}$$
$$W_{rec} \approx large \iff \text{  Exploding}$$
### Solutions:

1. Exploding Gradient:
	- Truncated Backpropagation
	- Penalties 
	- Gradient Clipping
2. Vanishing Gradient:
	- Weight Initialization
	- Echo State Networks
	- Long Short-Term Memory Neworks ([[LSTM]])

### Additional Reading

- [Long Short-Term Memory](https://www.semanticscholar.org/paper/Long-Short-Term-Memory-Hochreiter-Schmidhuber/2e9d221c206e9503ceb452302d68d10e293f2a10)
- [Learning long-term dependencies with gradient descent is difficult](https://www.semanticscholar.org/paper/Learning-long-term-dependencies-with-gradient-is-Bengio-Simard/d0be39ee052d246ae99c082a565aba25b811be2d)
- [On the difficulty of training recurrent neural networks](https://www.semanticscholar.org/paper/On-the-difficulty-of-training-recurrent-neural-Pascanu-Mikolov/84069287da0a6b488b8c933f3cb5be759cb6237e)

