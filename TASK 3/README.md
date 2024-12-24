# Image Encryption and Decryption

This project provides a Python script to encrypt and decrypt images using a random swapping algorithm based on a user-defined key. It ensures that the original image can be restored by using the same key for decryption.

## Features

- Encrypts an image by randomly swapping pixel values.
- Decrypts the image to its original form using the same key.
- Uses the Python Imaging Library (Pillow) for image manipulation.

## Requirements

- Python 3.x
- Pillow library

## Installation

1. Clone this repository:
   ```bash
   git clone 
   cd <repository-folder>
   ```

2. Install the required library:
   ```bash
   pip install pillow
   ```

## Usage

### Encrypt an Image

```python
encrypt_image('input_image.png', 'encrypted_image.png', key=12345)
```

- Replace `input_image.png` with the path to your input image.
- Replace `encrypted_image.png` with the desired output path for the encrypted image.
- Replace `12345` with your chosen encryption key.

### Decrypt an Image

```python
decrypt_image('encrypted_image.png', 'decrypted_image.png', key=12345)
```

- Replace `encrypted_image.png` with the path to your encrypted image.
- Replace `decrypted_image.png` with the desired output path for the decrypted image.
- Use the same key (`12345` in this example) that was used for encryption.

## File Structure

```
.
├── image_encryption.py       # The main script
├── input_image.png           # Example input image
├── encrypted_image.png       # Encrypted output image
├── decrypted_image.png       # Decrypted output image
├── README.md                 # Project documentation
```

## Example

1. Encrypt an image:
   ```bash
   python image_encryption.py
   ```

2. Decrypt the image:
   ```bash
   python image_encryption.py
   ```

## Disclaimer

This script is for educational purposes only. It is not intended for high-security encryption. For secure encryption, consider using established cryptographic libraries.

