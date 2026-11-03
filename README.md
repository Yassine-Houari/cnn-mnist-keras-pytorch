# CNNs on MNIST with Keras and PyTorch

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)

A practical study of convolutional neural networks: a simple CNN built in Keras and in PyTorch, compared with VGG-16 and ResNet-18 transfer learning on MNIST.

## Results

Test accuracy on the 10,000 MNIST test images:

| Model | Test accuracy |
| --- | --- |
| Simple CNN | **99.18%** |
| VGG-16 (transfer learning, 3 epochs) | 98.90% |
| ResNet-18 (transfer learning, 3 epochs) | 96.59% |

## Getting started

```bash
pip install -r requirements.txt
jupyter notebook cnn_mnist_keras_pytorch.ipynb
```

## Author

**Yassine Houari** · [LinkedIn](https://www.linkedin.com/in/yassine-houari-/)

Completed as pair work.
