# Image Editing Script

This Python script uses the Pillow (PIL) library to perform various image editing operations on a set of images.

## Overview

The script does the following:

1. Reads images from a directory specified by the `path` variable.
2. Applies the following edits to each image:
   - Sharpening the image using the `ImageFilter.SHARPEN` filter.
   - Converting the image to grayscale (black and white) using the `convert('L')` method.
   - Rotating the image 90 degrees counter-clockwise using the `rotate(-90)` method.
   - Enhancing the contrast of the image by a factor of 1.5 using the `ImageEnhance.Contrast` method.
3. Saves the edited images to a directory specified by the `pathOut` variable, with the filename modified to include `_edited`.

You can add more image editing operations from the [Pillow documentation](https://pillow.readthedocs.io/en/stable/) by modifying the code within the loop.

## Requirements

- Python 3.x
- Pillow (PIL) library: `pip install pillow`

## Usage

1. Ensure you have the required dependencies installed.
2. Place the unedited images in the directory specified by the `path` variable.
3. Run the script.
4. The edited images will be saved in the directory specified by the `pathOut` variable.

## Customization

You can customize the script by:

- Changing the directory paths for the input and output images.
- Modifying the image editing operations performed on the images.
- Adding additional image editing operations from the Pillow documentation.

## License

This script is licensed under the [MIT License](LICENSE).
