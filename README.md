# TensorFlow MNIST Autoencoder

A two-layer encoder-decoder that compresses MNIST images to a 64-dimensional latent representation and reconstructs them.

## Run

Use Python 3.10 with the pinned dependencies:

```bash
python -m pip install -r requirements.txt
python autoencoder.py
```

Keras downloads MNIST on first run. Training runs for 20,000 steps and then displays original and reconstructed images.

## Attribution

The notebook credits Aymeric Damien and the [TensorFlow-Examples project](https://github.com/aymericdamien/TensorFlow-Examples/).