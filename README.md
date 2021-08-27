sklearn digits dataset ([link](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_digits.html)) but with translation jitter added (from -3 to +3 pixels).

Used to test ML algos' invariance to translation.


Related:

- [xtomasch/kernels_and_dataset_centering.py](https://gist.github.com/xtomasch/84d1d8574ef51eb8d42e77560d647e06): Simple test to support my oppininon that RBF kernel does not benefit from centering
  - In fact, the notebook just demonstrates RBF insensitivity to "translation" meaning scale for 1D data, not translation of 2D images.
