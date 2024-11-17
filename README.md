# Image Encryption Tool

This is a simple Python-based image encryption tool that uses pixel manipulation techniques like swapping pixel channels and applying a basic mathematical operation (XOR) to encrypt and decrypt images. The tool is implemented using Python with the `Pillow` and `numpy` libraries.

## Features
- **Encrypt**: Swap pixel channels and apply an XOR operation to encrypt the image.
- **Decrypt**: Reverse the encryption steps to restore the original image.
- **Mathematical Operation**: XOR operation with a constant key for pixel manipulation.
  
## Requirements

To run this tool locally, you will need Python installed along with the `Pillow` and `numpy` libraries. You can also run this tool in Google Colab for easy setup and execution.

### Local Setup

1. Install Python from the [official website](https://www.python.org/downloads/).
2. Install the required libraries by running the following command in the terminal or command prompt:

   ```bash
   pip install pillow numpy
