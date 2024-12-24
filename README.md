# U-Net Image Segmentation with TensorFlow

## Overview
This project implements a **U-Net model** for semantic segmentation using TensorFlow. Instead of highlighting objects with bounding boxes, this project classifies elements such as roads, vehicles, trees, buildings, and zebra crossings at the pixel level, assigning specific colors to respective elements. This approach provides a deep understanding of each pixel's category, making it an essential building block for advanced applications like self-driving cars.

## Features
- **Pixel-level Classification**: Assigns colors to pixels to indicate their respective categories (roads, vehicles, etc.).
- **U-Net Architecture**: Includes encoder-decoder with skip connections.
- **Scalable Design**: Though this U-Net is smaller compared to the original paper's version, it demonstrates the building blocks and can be scaled for larger datasets.
- **Practical Applications**: A powerful tool for self-driving cars when trained on larger datasets.
- **Data Processing**: Uses TensorFlow `tf.data.Dataset` for efficient data preprocessing and augmentation.

## Dataset
- **Images**: Stored in `./data/CameraRGB/`.  
- **Segmentation Masks**: Stored in `./data/CameraMask/`.




