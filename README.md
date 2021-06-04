# ANPR-Using-OpenCV-and-PyTorch
This project aims to implement basic ANPR(Automatic Number Plate Recognition system) using OpenCV and Easyocr (PyTorch) in Python. The program extracts the number plate information from a picture or a static videoframe and stores it in CSV file with date of entry.

# What is ANPR ?

Automatic number-plate recognition is a technology that uses optical character recognition on images to read vehicle registration plates to create vehicle location data. It can use existing closed-circuit television, road-rule enforcement cameras, or cameras specifically designed for the task. ANPR is an advanced version of what I am going to show you in this article. Here, we will be implementing the software part. The hardware part can be implemented using CCTV cameras and Raspberry Pi.

# Steps involved :

1. Read the original image.
2. Convert it to grayscale and blur.
3. Apply filter and find edges for localization.
4. Find the contours and apply mask.
5. Read the text using Easyocr.
6. Render Result.
