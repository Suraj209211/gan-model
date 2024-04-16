# Generative Adversarial Network for Image Super Res

This repository contains a TensorFlow implementation of a Generative Adversarial Network (GAN) for generating images of handwritten digits (MNIST dataset).

## Overview

Generative Adversarial Networks (GANs) consist of two neural networks, a generator and a discriminator, which are trained simultaneously through a competitive process. The generator aims to produce realistic samples, while the discriminator aims to distinguish between real and generated samples. Through iterative training, the generator learns to generate increasingly realistic samples, while the discriminator becomes more adept at distinguishing real from fake.

## Requirements

- Python 3.x
- TensorFlow 2.x
- NumPy
- Matplotlib (for visualization)

## Usage

1. Clone the repository:

2. Train the GAN model:

3. Generate images using the trained model:


## Results

After training the model, generated images will be saved in the `generated_images` directory. You can visualize the generated images using the provided scripts or any image viewer.

## References

- Original GAN paper by Ian Goodfellow et al.: [Generative Adversarial Nets](https://arxiv.org/abs/1406.2661)
- TensorFlow documentation: [https://www.tensorflow.org](https://www.tensorflow.org)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This implementation is inspired by various GAN tutorials and examples available online.
- Special thanks to the TensorFlow community for their valuable contributions and resources.

