# Image Classifier

This image classifier was made using a convolutional neural network which is trained to classify if a given image is of a cat or a dog.

## About this model:
- The first layer of this neural network takes the flattened pooling layer as input. The pooling layer itself uses the ``max-pooling`` operation.
- The internal layers use the rectified linear unit activation function (``relu``) for learning.
- The network makes use of Adam optimizer because it extends the stochastic gradient descent and updates the synaptic weights more efficiently.
- The network uses binary cross entropy loss function and has been trained over ``25`` epochs.
- The final calculated accuracy is ``91.65%``.

---
### Tools used:
- Keras : https://keras.io/api/
- NumPy : https://numpy.org/doc/stable/reference/index.html#reference
- Python : https://docs.python.org/3/
- TensorFlow : https://www.tensorflow.org/api_docs/python/tf
<br>

> NOTE: The dataset on which it was trained and tested on was very large (approximately ``200MB``) in size, and hence, could not be uploaded.
