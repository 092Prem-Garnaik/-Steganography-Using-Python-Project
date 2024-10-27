# -Steganography-Using-Python-Project
# Steganography - Hide a Secret Text Message in an Image

This project implements a simple steganography tool using Python that allows users to hide a secret text message within an image file (PNG or JPG) and retrieve it later. The application leverages the `stegano` library for the encoding and decoding process.

## Features

- **Hide a Message:** Embed a secret text message into an image file.
- **Retrieve a Message:** Extract the hidden message from the image.
- **User-friendly GUI:** Built with Tkinter for easy interaction.
- **Image Preview:** Displays a preview of the selected image.

## Prerequisites

- Python 3.x
- Required Libraries:
  - `PIL` (Pillow)
  - `stegano`
  - `tkinter` (comes with standard Python installations)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/steganography-app.git
cd steganography-app
pip install Pillow stegano
python your_script_name.py
