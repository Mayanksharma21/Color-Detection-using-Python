# Project Name

Color Picker - A Python application to detect the color name and RGB values of a pixel in an image.

## Introduction

This project is a Python application that allows the user to select an image and identify the color name and RGB values of any pixel in the image. The application displays the selected image and tracks the user's double-click on a pixel. Upon detection of a double-click, the application identifies the color of the pixel and displays the color name and RGB values.

## Technologies Used

The following technologies were used in this project:

- Python 3.5+
- OpenCV: Used for image reading, display and pixel manipulation
- Pandas: Used to read and manipulate the CSV file containing color data
- Tkinter: Used to display the file dialog box for selecting the image file

## Usage

To use this project, follow these steps:

1. Clone the repository to your local machine using the following command:
   ```bash
   git clone https://github.com/Mayanksharma21/Color-Detection-using-Python.git
2. Install the required libraries using the following command:
   ```bash
   pip install opencv-python pandas tkinter
3. Update the csv_path variable in the color_picker.py file with the path to the colors.csv file.
4. Navigate to the directory containing the color_picker.py file.
5. Run the following command to start the application:
   ```bash
   python color_picker.py
6. The application will open a file dialog box allowing you to select an image.
7. Once an image is selected, the application will display the image and track your mouse movements.
8. Double-click on any pixel in the image to display the color name and RGB values.
9. Press the Esc key to exit the application.
