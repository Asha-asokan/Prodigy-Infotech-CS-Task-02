# Prodigy-Infotech-CS-Task-02
# Image Encryption and Decryption
This project provides a simple Python-based tool to encrypt and decrypt images using an XOR encryption technique. The program takes an image file as input, applies an XOR operation to each pixel's RGB values using a specified key, and saves the result as an encrypted image. The same key can be used to decrypt the image back to its original state.
# Features
- Encrypt Image: Securely obfuscates image data using a specified key.
- Decrypt Image: Reverts encrypted images back to their original form using the same key.
- Simple XOR Encryption: Uses a basic XOR operation for encryption and decryption.

# Project Structure
- encrypt_image(input_image_path, output_image_path, key): Encrypts an image file using an XOR operation on each pixel.
- decrypt_image(encrypted_image_path, output_image_path, key): Decrypts an XOR-encrypted image file, restoring the original image.
- main: Executes both encryption and decryption on a sample image for demonstration.

 # Getting Started

# Prerequisites
- Python 3.x
- Pillow (PIL): Image processing library. Install via pip:
pip install pillow

# Encryption Details
- Algorithm: XOR-based encryption
- Key: A single integer key used to encrypt and decrypt each pixel's RGB values.
