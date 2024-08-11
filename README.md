# Image Steganography with Tkinter GUI

This project implements image steganography using Python with a graphical user interface (GUI) built with Tkinter. It allows users to hide (encode) and extract (decode) secret messages within images while maintaining the image's visual integrity.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
  - [Running the Application](#running-the-application)
  - [Encoding a Message](#encoding-a-message)
  - [Decoding a Message](#decoding-a-message)
- [Dependencies](#dependencies)
- [Contributing](#contributing)

## Introduction

This image steganography project provides a simple, user-friendly interface to hide or reveal text within images. The application supports various image formats such as PNG, JPEG, and JPG. It also includes a password protection feature to secure the hidden data.

## Features

- **Encode Text**: Hide secret messages within images.
- **Decode Text**: Extract hidden messages from encoded images.
- **Password Protection**: Optionally secure the hidden data with a password.
- **GUI Interface**: User-friendly GUI using Tkinter for ease of use.

## Installation

### Clone the Repository

First, clone the repository to your local machine:

```bash
git clone https://github.com/yourusername/image-steganography-tkinter.git
cd image-steganography-tkinter
```

## Install Dependencies
Install the required Python packages using pip:

```bash
pip install -r requirements.txt
```

Note: The requirements.txt should include at least the following:
Pillow

## Usage
### Running the Application
To run the application, simply execute the following command in your terminal:

```python
python steganography.py
```

This will launch the Tkinter GUI for the image steganography tool.

## Encoding a Message
- Start the Application: Click on the "Encode" button in the main menu.
- Select an Image: Choose the image in which you want to hide the message.
- Enter the Message: Input the text you wish to hide.
- Set a Password (Optional): Set a password to secure the hidden message.
- Save the Encoded Image: The modified image with the hidden message will be saved.

## Decoding a Message
- Start the Application: Click on the "Decode" button in the main menu.
- Select an Encoded Image: Choose the image that contains the hidden message.
- Enter the Password (if set): Provide the password used during encoding.
- Retrieve the Message: The hidden message will be displayed.

## Dependencies
- Python 3.x
- Pillow: Used for image processing.
- Tkinter: Built-in Python module for creating GUI applications.
You can install the dependencies using:

```python
pip install Pillow
```

## Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue for any bugs or improvements.
