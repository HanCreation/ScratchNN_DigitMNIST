# ScratchNN_DigitMNIST
NN for [Digit Recognizer (MNIST)](https://yann.lecun.com/exdb/mnist/index.html). Created using only Numpy and Math
---
 Built a simple neural network from scratch using only NumPy, without relying on any high-level libraries like TensorFlow, PyTorch, or Keras. The task was to classify digits from the MNIST dataset, which contains images of handwritten digits.

 ## What I learned
 - Get to know MNIST: Basic dataset for learning computer vision, and one of the MNIST is the digit recognizer
 - Numpy syntax and how to use it 
 - Visualizing math formula for forward/backward pass including each matrix/vector size
 - Converting math formula/equation into syntax
 - Creating basic network architecture without high-level libraries
 - Making function of weight initialization, forward pass, gradient descent, backward pass, update parameter, etc in python
 - Softmax and ReLU function and its derivative

 ## Update
 I just found out that torch and numpy have similar syntax, so I try to create another version with torch and with some support to GPU compute (Which overkill lol)

 Similarities:
 - np.array ; torch.tensor
 - np.random.randn ; torch.randn
 - np.maximum ; torch.max
 - np.exp ; (tensor variable).exp()
 - np.dot ; using @ syntax to do matrix mul
 - np.sum ; (tensor var).sum() -> the keepdim parameter is important, and the axis too
 - np.argmax ; torch.argmax

 Add on notes:
 - Torch has integrated one hot encoding function (torch.nn.Functional.one_hot)
 - Shuffling tensor is not straight forward like using np.shuffle
 - Always check the shape of the tensor

---
Coded and Created by Han Summer 2024

Part of The 20th Summer Project
