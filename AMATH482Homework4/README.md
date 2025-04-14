This report documents the design, implementation, and optimization of a Fully Connected Neural Network
(FCN) for classifying the FashionMNIST dataset. The FCN was built with adjustable architecture param-
eters, including the number of layers, neurons, learning rate, and training epochs. The project explored
baseline configurations and hyperparameter tuning, testing various optimizers (SGD, Adam, RMSProp),
regularization techniques (Dropout), weight initialization methods (Random Normal, Xavier, Kaiming), and
Batch Normalization. Results demonstrate that hyperparameter choices significantly influence training loss,
validation accuracy, and test accuracy. The final configurations achieved over 89% accuracy on the test set
with eﬀective generalization and stable training behavior.
