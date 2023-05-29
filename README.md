# Style Transfer with PyTorch

This repository contains code and resources for performing style transfer on images using deep learning techniques. The project focuses on transferring the style of one image (the style image) onto another image (the content image), creating visually appealing and artistic results. The project is implemented in Python using the PyTorch framework.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Training](#model-training)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Style transfer is a technique that uses deep learning to transfer the style of one image onto another image. The technique was first introduced in the paper [A Neural Algorithm of Artistic Style](https://arxiv.org/abs/1508.06576) by Gatys et al. The paper describes a method for transferring the style of one image onto another image using convolutional neural networks. The method uses a pre-trained convolutional neural network to extract features from the style image and the content image. The style of the style image is then transferred onto the content image by minimizing the mean squared distance between the feature maps of the style image and the content image. The method is able to produce visually appealing and artistic results.

This project implements the method described in the paper by Gatys et al. using the PyTorch framework. The project contains code and resources for performing style transfer on images using deep learning techniques. The project contains a dataset of images that can be used for training the model. The project also contains a pre-trained model that can be used for performing style transfer on images. The project contains code for training the model and code for performing style transfer on images using the pre-trained model.

## Installation

To use the code in this repository, follow these steps:

1. Clone the repository

```shell
git clone https://github.com/ArnabKumarRoy02/Style-Transfer.git
```

2. Install the dependencies

```shell
pip install -r requirements.txt
```

## Usage

Here's a breif overview of the main files and directories in the repository:

- `Images/` - Contains images that can be used for training the model.
- `utils.py` - Contains utility functions for loading and saving images, displaying images, and computing the gram matrix.
- `style_transfer.py` - Contains functions for performing style transfer on images.
- `Results/` - Contains images that were generated using the trained model.

To perform style transfer on an image, run the following command:

```shell
python style_transfer.py --content path/to/content_image --style path/to/style_image --output path/to/output_image
```

Make sure to replace `path/to/content_image` with the path to the content image, `path/to/style_image` with the path to the style image, and `path/to/output_image` with the path to the output image.

## Dataset

This project does not require a specfic dataset, as it focuses on transferring the style from one image to another. You can use any content and style images of your choice.

## Model Training

This project does not require any model training, as it contains a pre-trained model that can be used for performing style transfer on images. The models used for style transfer are pre-trained on large datasets of images, such as the [ImageNet](https://www.image-net.org/update-mar-11-2021.php) dataset. Therefore, no model training is required in this repsitory. The focus is on the application and use of pre-trained models for style transfer.

## Examples

The `Results/` directory contains images that were generated using the pre-trained model. Here is an examples:

![Result](https://github.com/ArnabKumarRoy02/Style-Transfer/blob/main/Results/shrek_spagetti.jpg)
<p align-content="center">
    <em>Style transfer on Shrek and spaghetti</em>
</p>

## Contributing

Contributions to this project are welcome! If you have any suggestions or run into any issues, feel free to open an issue or create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
