# PRODIGY_CS_02

# Simple Image Encryption Tool

This is a simple image encryption tool implemented in Python that uses basic pixel manipulation techniques to encrypt and decrypt images. The tool allows users to swap pixel values and apply a mathematical operation to each pixel, providing a basic level of image encryption.

## Features

- Encrypt images by manipulating pixel values.
- Decrypt images back to their original form.
- Simple and easy-to-understand implementation.

## Requrements

- Python 3.x
- Pillow (PIL Fork)
- NumPy

## Explanation

Encrypt Function:

Reads the input image and converts it to a NumPy array.
Swaps pixel values with the next pixel in the row.
Adds a constant value (50 in this case) to each pixel value, wrapping around using modulo 256 to keep pixel values valid (0-255).
Saves the modified array as a new image.
Decrypt Function:

Reads the encrypted image and converts it to a NumPy array.
Subtracts the constant value (50) from each pixel.
Swaps the pixel values back to their original positions.
Saves the modified array as a new image.
Usage
Replace 'input_image.png' with the path to your image file.
Run the script, and it will create an encrypted image and then decrypt it back to the original.
## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Adhith708/image-encryption-tool.git
   cd image-encryption-tool

### Usage

- Replace 'input_image.png' with the path to your image file.
- Run the script, and it will create an encrypted image and then decrypt it back to the original.

### Example

- Original Image 

![Minimalist Aesthetic Desktop Wallpaper _ TheCandie_com](https://github.com/user-attachments/assets/ad02a5bc-6e9c-4212-a1a2-a7f141560e99)

- Image After Encryption

![Screenshot (71)](https://github.com/user-attachments/assets/d898a740-2155-445a-9237-dc427274fd8c)

- Image After Decryption

![Screenshot (72)](https://github.com/user-attachments/assets/b97a88ce-63f0-48fb-911a-d3de46d630f2)
