# Image_to_Pencilsketch
To convert an image to a pencil sketch using a simple algorithm in Python, you can follow these steps:

Load the image using a library such as PIL (Python Imaging Library) or OpenCV.
Convert the image to grayscale.
Invert the grayscale image.
Apply a Gaussian blur to the inverted image to smooth out details.
Blend the grayscale image with the blurred image using a technique called dodge blending.
