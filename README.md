# Contextual Corrections
Reproducing the results of the paper by [Mutmainah et. al. 2022](https://link.springer.com/chapter/10.1007/978-3-031-17801-6_11) on image recognition datasets

The notebook includes an experiment on the MNIST dataset, running experiments on similar datasets like FashionMNIST and CIFAR10 requires small adjustments:
*    in the **"Data loading"** section (changes to dataset names and train/val sizes)
*    in the **"Models"** section, as it is preferable to use bigger models for other more complex datasets

Credit to **paul-bd** for their [implementation of the evidential layers](https://github.com/paul-bd/DempsterShaferTheory)

Credit to **tongzheng1992** for their [jupyter notebook and utility layer](https://github.com/tongzheng1992/E-CNN-classifier)

