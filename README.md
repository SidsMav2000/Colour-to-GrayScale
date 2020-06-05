# Colour to BW
A Python script to convert a coloured image into a Black and White version of the same (without any loss in image quality).

This is a very simple Python script takes a colored image filename as argument and converts it into grayscale image and saves the output image file, showing the basic usage of the Pillow library.

Libraries Required:
Pillow (pil) 

`pip install Pillow`

Usage
Go to the script's folder and open the terminal/command prompt.

Run command : `$python bw_convert.py <image_file_name>`

Example:

`$python bw_convert.py sample_image.jpg`

This duplicates `sample_image.jpg` and then converts it to/saves it as `bw_sample_image.png` in the same directory.
