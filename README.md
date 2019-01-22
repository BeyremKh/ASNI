# ASNI

Dropout is a regularisation technique in neural network training where unit activations are randomly set to zero with a given probability independently. In this work, we propose a generalisation of dropout and other multiplicative noise injection schemes for shallow and deep neural networks, where the random noise applied to different units is not independent but follows a joint distribution that is either fixed or estimated during training. We provide theoretical insights on why such adaptive structured noise injection (ASNI) may be relevant, and empirically confirm that it helps boost the accuracy of simple neural networks, disentangles the hidden layer representations, and leads to sparser representations.

## Results

![MNIST 32 activations](http://jcboyd.github.io/assets/ANSI/mnist_new_32.html)

![MNIST 64 activations](http://jcboyd.github.io/assets/ANSI/mnist_new_64.html)

![MNIST 256 activations](http://jcboyd.github.io/assets/ANSI/mnist_new_256.html)

![MNIST 512 activations](http://jcboyd.github.io/assets/ANSI/mnist_new_512.html)

![MNIST 1024 activations](http://jcboyd.github.io/assets/ANSI/mnist_new_1024.html)

![MNIST fast](http://jcboyd.github.io/assets/ANSI/mnist_new_fast.html)

![CIFAR-10](http://jcboyd.github.io/assets/ANSI/struc_dropout_cifar10_new.html)

![CIFAR-10 fast](http://jcboyd.github.io/assets/ANSI/struc_dropout_cifar10_fast.html)

![CIFAR-100](http://jcboyd.github.io/assets/ANSI/strucorr_dropout_cifar100_new.html)

![CIFAR-100 fast](http://jcboyd.github.io/assets/ANSI/strucorr_dropout_cifar100_fast.html)

![MNIST varying](http://jcboyd.github.io/assets/ANSI/structured_dropoutmnist_varying.html)

![Simulation](http://jcboyd.github.io/assets/ANSI/Simul_struc_drop_fast.html)
