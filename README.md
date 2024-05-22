# Modified-Small-dataset

This is a repopsitory of experiments conducted on a standard dataset and then keeping the image size same, the contents inside the dataset is made smaller. Then two networks with same architecture are trained on both the datasets and then tested on their own datsets and then the other datasets.

For Example, one CNN is trained on standard MNIST and another CNN is trained on modified MNIST, then the MNIST trained on standard MNIST is tested on standard MNIST and modified MNIST, then the CNN trained on modified MNIST is tested on standard MNIST and then on modified MNIST.

The experiments have been conducted on MNIST, Fashion MNIST, CIFAR-10 and CIFAR-100 for now.
