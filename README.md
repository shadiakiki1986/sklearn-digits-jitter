sklearn digits dataset with translation jitter added (from -3 to +3 pixels).

Used to test ML algos' invariance to translation.

Related links:

- [sklearn.datasets.load_digits](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_digits.html)
- [sklearn/docs/datasets/digits](https://scikit-learn.org/stable/datasets/toy_dataset.html#digits-dataset):
  - Quote: "For info on NIST preprocessing routines, see M. D. Garris, J. L. Blue, G. T. Candela, D. L. Dimmick, J. Geist, P. J. Grother, S. A. Janet, and C. L. Wilson, NIST Form-Based Handprint Recognition System, NISTIR 5469, 1994."
- [xtomasch/kernels_and_dataset_centering.py](https://gist.github.com/xtomasch/84d1d8574ef51eb8d42e77560d647e06): Simple test to support my oppininon that RBF kernel does not benefit from centering
  - In fact, the notebook just demonstrates RBF insensitivity to "translation" meaning scale for 1D data, not translation of 2D images.
- [svm-rbf-sensitivity-to-translation.ipynb](https://gist.github.com/shadiakiki1986/689980135fe9dde1d892127bde40a5a1): demo of sensitivity of SVM RBF to translation jitter
