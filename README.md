sklearn digits dataset with translation jitter added (from -3 to +3 pixels).

Used to test ML algos' invariance to translation.

Example usage of this dataset:

- [svm-rbf-sensitivity-to-translation.ipynb](https://gist.github.com/shadiakiki1986/689980135fe9dde1d892127bde40a5a1): demo of sensitivity of SVM RBF to image 2d translation jitter


Related links:

- [sklearn.datasets.load_digits](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_digits.html)
- [sklearn/docs/datasets/digits](https://scikit-learn.org/stable/datasets/toy_dataset.html#digits-dataset):
  - Quote: "For info on NIST preprocessing routines, see M. D. Garris, J. L. Blue, G. T. Candela, D. L. Dimmick, J. Geist, P. J. Grother, S. A. Janet, and C. L. Wilson, NIST Form-Based Handprint Recognition System, NISTIR 5469, 1994."
- [xtomasch/kernels_and_dataset_centering.py](https://gist.github.com/xtomasch/84d1d8574ef51eb8d42e77560d647e06): test that RBF kernel does not benefit from ~~~centering~~~ normalization
  - this demonstrates RBF insensitivity to "translation" meaning scale for 1D data, not translation of 2D images.
- [MNIST digits dataset](http://yann.lecun.com/exdb/mnist/): "the images were centered in a 28x28 image by computing the center of mass of the pixels, and translating the image so as to position this point at the center of the 28x28 field"
