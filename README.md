# Handwritten Digit Recognition
The handwritten digit recognition is the ability of computers to recognize human handwritten digits. It is a hard task for the machine because handwritten digits are not perfect and can be made with many different flavors. The handwritten digit recognition is the solution to this problem which uses the image of a digit and recognizes the digit present in the image. Datasets is loaded from the inbuilt library of Keras.

# The MNIST dataset
This is probably one of the most popular datasets among machine learning and deep learning enthusiasts. The [MNIST dataset](http://yann.lecun.com/exdb/mnist/) contains 60,000 training images of handwritten digits from zero to nine and 10,000 images for testing. So, the MNIST dataset has 10 different classes. The handwritten digits images are represented as a 28×28 matrix where each cell contains grayscale pixel value.

# Coding on Google Colab

1. Import the libraries and load the dataset
<img target="_blank" src="https://64.media.tumblr.com/2b7e394673b8c7bb67d076de57af0d54/7d9fe0e8c295eea3-39/s1280x1920/afaa604c2a610e2c8c5a61c6fe40f444831fc773.png">

2. Preprocessing the data
<img target="_blank" src="https://64.media.tumblr.com/2da3b2adabb8d3623fdd8168d16309c9/7d9fe0e8c295eea3-b5/s1280x1920/49e9fc2222772df0fca11e6bf0823045e7029a0f.png">

3. Creating the model
<img target="_blank" src="https://64.media.tumblr.com/be4c14c7311b3ae633e0399b26da8f93/7d9fe0e8c295eea3-91/s1280x1920/79675abeb7b712d9fdee40bd87cdb4e69ffb9521.png">

4. Training the model
<img target="_blank" src="https://64.media.tumblr.com/c27709b5efbcd8493142aef9058ea5d6/7d9fe0e8c295eea3-bb/s1280x1920/a84d3786dd44c1e5d38396f7f422eb1c0614a089.png">

5. Save the model as "mnist.h5"
<img target="_blank" src="https://64.media.tumblr.com/ea407f217f1ac7b50b2c16c6feacb5d8/efd72c215d3a98aa-48/s1280x1920/11f88a015cdf99d997a047b5527645a98527e51a.png">

6. Evaluating the model
<img target="_blank" src="https://64.media.tumblr.com/3194b3574e2961fecee5d96886a2f6c7/efd72c215d3a98aa-0e/s1280x1920/6504524066943a71342e288654ea4fc8ae1b2f7f.png">

7. Plot the graph of Accuracy vs Loss
<img target="_blank" src="https://64.media.tumblr.com/9ecabb1af0cdc7c252509500c0aa12da/efd72c215d3a98aa-8a/s1280x1920/ec4cd53c00a841be55f16bde9dc209ea8ddc0375.png">

## Technologies Used
[<img target="_blank" src="https://www.gstatic.com/devrel-devsite/prod/vbd0faab6c0701e17b2f66039dd03326fc0e1627ecbcddaec4cd383df8dda622c/tensorflow/images/lockup.svg" height=50>](https://www.tensorflow.org/) [<img target="_blank" src="https://keras.io/img/logo-small.png" height=50>](https://keras.io/) [<img target="_blank" src="https://matplotlib.org/stable/_static/logo2_compressed.svg" height=50>](https://matplotlib.org/stable/index.html)
## Directory Tree 
```
├── Handwritten_Digit_Recognition.ipynb
├── README.md
├── mnist.h5
```
