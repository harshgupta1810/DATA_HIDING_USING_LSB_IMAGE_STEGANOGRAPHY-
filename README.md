# Data Hiding using LSB Image Steganography

This repository contains code for hiding a message within an image using the Least Significant Bit (LSB) technique of steganography.

## Encoding the Message

- The original image (`cat.jpg`) is read and converted to grayscale.
- The user is prompted to enter the message they want to hide within the image.
- The message is converted into binary format, where each character is represented by 8 bits.
- LSB of the grayscale intensity of each pixel is modified to embed the message bits.
- The resulting stego image is displayed alongside the original cover image.

## Decoding the Message

- The LSB of each pixel in the stego image is extracted to retrieve the hidden message bits.
- The binary message bits are converted back into characters to reveal the original message.

## Instructions

1. Ensure MATLAB is installed.
2. Run the script.
3. Enter the message you want to hide within the image when prompted.
4. The script will display the cover image and the stego image with the hidden message.
5. After decoding, the original message will be displayed.

## Note

- This code is for educational purposes only.
- The steganographic method used here is relatively basic and may not be suitable for high-security applications.

## Author

This code is authored by [Your Name] and is provided under the [license type].

For any questions or issues, please contact [author email].
