# BMP Image Editor✍️

This project is a BMP image editor that allows users to open, view, and manipulate BMP images. The editor provides functionalities to adjust brightness, scale the image, and toggle RGB channels.

## Features

- Open and display BMP images.
- View image metadata (file size, width, height, bits per pixel).
- Adjust image brightness.
- Scale the image.
- Toggle RGB channels (Red, Green, Blue).

## Requirements

- Python 3.x
- `tkinter` (usually included with Python)
- `Pillow` (Python Imaging Library)
- `numpy` (Numerical Python)

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/yourusername/bmp-image-editor.git
    cd bmp-image-editor
    ```

2. Install the required dependencies:

    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Run the program:

    ```sh
    python bmpparser.py
    ```

2. Use the GUI to open a BMP file and manipulate the image using the provided tools.

## File Structure

- [bmpparser.py]: Main script containing the BMP image editor implementation.
- [requirements.txt]: List of dependencies required to run the project.
- [PA1_Sample_Input]: Image samples for 1, 4, 8, 24 bpp images.

## How It Works

1. **Open BMP File**: Use the "Open BMP File" button to select and open a BMP file. The program reads the file and checks if it is a valid BMP file.
2. **View Metadata**: The metadata of the BMP file (file size, width, height, bits per pixel) is displayed.
3. **Adjust Brightness**: Use the brightness slider to adjust the brightness of the image.
4. **Scale Image**: Use the scale slider to scale the image.
5. **Toggle RGB Channels**: Use the toggle buttons to enable or disable the Red, Green, and Blue channels.

## Example

<img width="512" alt="BIOS" src="https://github.com/user-attachments/assets/ee59964d-f3ad-48ef-b5b9-edd671f95ac2" />
<img width="512" alt="red" src="https://github.com/user-attachments/assets/7e1493b0-912f-43f4-8efb-f196869ef33c" />

## Author

Yecheng Wang

This project is part of an assignment for CMPT365 @ Simon Fraser University
