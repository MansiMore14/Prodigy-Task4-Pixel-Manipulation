# Prodigy-Task4-Pixel-Manipulation
Overview

This program performs simple image encryption and decryption by manipulating pixel color channels. It works by swapping the red and blue channels of each pixel to obscure the image data. The process is reversible, allowing for decryption by swapping the channels back to their original positions.

Key Features

Image Encryption:
Encrypts images by swapping the red and blue channels of each pixel.
The result is an altered image where the original data is hidden.


Image Decryption:
Restores the original image by reversing the red-blue channel swap.
This ensures the image can be fully recovered without data loss.

User Input:

The program prompts the user for the input image path, output image path, and an optional key (not yet implemented).

Requirements

Python 3.x

Pillow Library (pip install pillow)

How It Works

Encryption: The program reads an image, swaps the red and blue channels of each pixel, and saves the encrypted image.

Decryption: The reverse operation restores the original image by swapping the channels back.
