## Long Short-Term Memory (intuition)

The whole idea behind LSTM is to, whenever an weight is too small that becomes smaller than a predefined threshold, let's say *1* for purposes of example you consider the weight to be that threshold, so in this example: *= 1*

$$W_{rec} = W_{rec} \text{  , if } W_{rec} \ge 1 $$
$$W_{rec} = 1 \text{  , if } W_{rec} \lt 1 $$

**LSTM Diagram:**
![[LSTM.png]]


![[LSTM_LEGEND.png]]

## Practical Intuition

It's like to have a nested `if` statements learned by the network, which considers previous states from a training set.

## LSTM - Variations

There are 3 variations for the classic LSTM architectures, which changes how the pointwise operations and flows are combined.

## Additional Reading

- [Long Short-Term Memory](https://www.semanticscholar.org/paper/Long-Short-Term-Memory-Hochreiter-Schmidhuber/2e9d221c206e9503ceb452302d68d10e293f2a10)
- [Visualizing and Understanding Recurrent Networks](https://www.semanticscholar.org/paper/Visualizing-and-Understanding-Recurrent-Networks-Karpathy-Johnson/40be3888daa5c2e5af4d36ae22f690bcc8caf600)
- [LSTM: A Search Space Odyssey](https://www.semanticscholar.org/paper/LSTM%3A-A-Search-Space-Odyssey-Greff-Srivastava/a7976c2bacfbb194ddbe7fd10c2e50a545cf4081)
- [Christopher Olah Blog - LSTM](https://colah.github.io/posts/2015-08-Understanding-LSTMs/)
- [Shi Yan Blog - LSTM](https://blog.mlreview.com/understanding-lstm-and-its-diagrams-37e2f46f1714)
- [Andrej Karpathy Blog - RNN Effectiveness](https://karpathy.github.io/2015/05/21/rnn-effectiveness/)

