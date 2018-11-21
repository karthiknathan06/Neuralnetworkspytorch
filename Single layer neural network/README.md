A simple neural network tutorial

What is a tensor?
Tensor is a core datastructure for pytorch ,like vectors and matrices, you can calculate arithmetic operations with tensors.
Simply like a numpy arrays

We have generated the features and weights data using randn function.Simply tensor.randn(m,n) generates a matrix of m rows and n columns which is filled with random numbers having randomseed as mentioned

Then we are having an activation function as sigmoid function
What is activation function:
Used to map the output of the neural networks from 0 to 1 or Yes or No(based on activation function used)

The sigmoid function is an activation function where it scales the values between 0 and 1 by applying a threshold.
![alt text](https://analyticsindiamag.com/wp-content/uploads/2018/01/sigmoid-1.png)

Finally 

 h = Wx + b
 
 where w is the weight,
 x is the feature,
 b is the bias
 
 Then fitting this value into activation function gives the probabilty value as output
 
 Here this is simple way of learning how a neural network works.
 But actual network consist of many hidden layers and various activation function and backpropagation is used to adjust the weights and bias value and Optimistic algorithms like gradient descent are used.
