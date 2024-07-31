# Cartoonification of an Image

This project uses OpenCV and Python to transform real images into cartoon-like animations. It detects objects in the image and applies various image processing techniques to achieve a stylized, cartoonish effect.

## Features

- Object detection and cartoon effect application
- Edge detection, smoothing, and color enhancement
- Simple command-line interface

## Requirements

- Python 3.x
- OpenCV (`opencv-python`)
- NumPy (`numpy`)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/cartoonification-of-an-image.git
    ```

2. Navigate to the project directory:

    ```bash
    cd cartoonification-of-an-image
    ```

3. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Place the image you want to cartoonify in the project directory.

2. Run the script:

    ```bash
    python cartoonify.py --input <your-image-file>
    ```

    Replace `<your-image-file>` with the name of your image file.

3. The cartoonified image will be saved in the project directory with the name `cartoonified_<your-image-file>`.

## Project Structure

- `cartoonify.py`: Script to cartoonify images.
- `requirements.txt`: Python packages required for the project.
- `README.md`: Project documentation.


## Contributing

Feel free to open issues or submit pull requests with suggestions or improvements.

