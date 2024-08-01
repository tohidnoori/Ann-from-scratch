# Artificial neural network


**Artificial neural network** (ANN) is a computational model inspired by the human brain, consisting of interconnected nodes (neurons) that process data in layers to recognize patterns and solve complex problems.
<br/>
<br/>
I built this model on myself using a single hidden layer and a single node for the outer layer.
I use **binary cross entropy** for my loss function and **Relu** and **Sigmoid** for my activation functions in this simple network.
I also use matrix multiplication and backpropagation to calculate the weights and biases of this network.
<br/>
The comparison between my model and the **tensor flow sequential model** is discussed at the end.
- - - -
#### These statistics are being examined right now: ####
 
#### These features of Ann studied here: ####
  * Diffirent optimizers (Adam,Adagrad,SGD,Rmsprop)
  * Diffirent activation functions (sigmoid,relu,tanh)
  * Epochs ,Batch size ,Learning rate ,Loss functions,N-jobs = ("Number of cpu cores to use")
    
- - - -
### Some equations used for the backprop process
<table>
  <tr>
    <td align="center">
      <img src="https://github.com/tohidnoori/Ann-from-scratch/blob/main/images/Hidden%20Layer%20weight's%20backpropagation.png" width="500" height="400" alt="Hidden layer weight's backpropagation">
      <p>Hidden layer weight's backpropagation</p>
    </td>
    <td align="center">
      <img src="https://github.com/tohidnoori/Ann-from-scratch/blob/main/images/Output%20Layer%20bias%20backpropagation.png" width="500" height="400" alt="Output layer bias backpropagation">
      <p>Output layer bias backpropagation</p>
    </td>
  </tr>
</table>
<div/>
