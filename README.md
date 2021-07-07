# All notebooks made in Google Colaboratory Pro

## Note:
None of these are good. I am still a complete beginner. If you have any tips, DM me on discord at rquit#8678.
Most if not all use mixed precision.
They are trained either on a v100 or p100, whichever one colab gave me. There is more details at the top of the nb.

## Convolutional_NN:
This notebook is what I used to explore fairly basic convolutional neural networks (CNN) using CIFAR-10. 
Loss function is Cross-Entropy loss, separated to log softmax and NLLLoss. 
Optimizer is Adam, although I had some decent results using SGD with momentum (0.9).

## RNN_LSTM:
This notebook explores the basics of LSTMs, and uses the book "Pride and Prejudice" by Jane Austen to train.
As with before, it uses Cross-Entropy Loss and the Adam optimizer.
Results turned out okay, I guess. Not great at all but at least the computer strings together some legible stuff.
