
## Day 1


*Sep 23, 2026*

- Calling g.backward() and then looking at a.grad tells you the change in g due to a (dg/da). So if a.grad = 140, then 1 unit increase in a -> 140 unit increase in g.

- Neural networks are just mathematical expressions that take input and weights of neural network as inputs, and output a prediction produced by the neural network. 

- Backpropagation is more general; juts happened to be used in training of NN
  - Work backwards to find gradients
- Usually use tensors (vectors, matrices etc.); scalars just for learning purposes

## Day 1


*Sep 26, 2026*

- Studying a lot of how to implement forward pass and back propagation (more manually of course)
- About to start learning the recursive algorithm

*Oct 1, 2026*

- Haven't been as consistent with learning log; have been doing a little bit consistently each day
- At the end of the day, NN is some function applied to input, giving us an output
- What operations included in values is up to you e.g. basic addition, multiplication vs more complex tanh or exponentials
- Check NN with forward pass v backward pass

- Micrograd is a scalar valued engine (only scalar values), but PyTorch uses tensors (n-dimensional arrays of scalars)
