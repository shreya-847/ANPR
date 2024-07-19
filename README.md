# ANPR
Automatic Number Plate Recognition (ANPR) is a technology used to read vehicle registration plates using optical character recognition on images. This project leverages the power of image processing techniques, particularly Canny edge detection, to identify and extract number plates from images of vehicles.

### Dependencies
To run this project, you need the following dependencies:

- opencv-python
- matplotlib
- easyocr
- imutils
- numpy

## File Descriptions

### 1. `img1.jpg`
An example image of a vehicle with a visible number plate. This image is used as input for the ANPR system to demonstrate its functionality.

### 2. `numberplate.csv`
A CSV file that stores the extracted number plate texts from the images processed by the ANPR system. Each row in the file corresponds to a detected number plate.

### 3. `WithoutYOLOANPR.ipynb`
A Jupyter Notebook containing the implementation of the ANPR system without using YOLO. It uses Canny edge detection and other image processing techniques to identify and read number plates from images.

## Results:

![results](https://github.com/user-attachments/assets/c8177189-011d-436a-9ce9-df40bb617c18)


Feel free to adjust the paths and details as per your specific requirements.
