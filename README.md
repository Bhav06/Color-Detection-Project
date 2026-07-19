# Color Detection Project

## Project Overview

This project detects the color of a pixel selected from an image using Python and OpenCV. When the user double-clicks on any point in the image, the application identifies the nearest matching color from a predefined color dataset and displays the color name along with its RGB values.

## Features

- Detects colors from an image using mouse double-click.
- Displays the detected color name.
- Shows RGB (Red, Green, Blue) values of the selected pixel.
- Uses a CSV dataset containing color names and RGB values.
- Simple and interactive graphical interface.

## Technologies Used

- Python 3
- OpenCV
- Pandas

## Project Files

```
ColorDetectionProject/
│── color_detection.py
│── colors.csv
│── colorpic.jpg
│── pic1.jpg
│── pic2.jpg
│── pic3.jpg
│── README.md
```

## Installation

Install the required Python libraries:

```bash
pip install opencv-python pandas
```

## How to Run

Run the following command from the project directory:

```bash
python color_detection.py
```

## How It Works

1. The program loads an image.
2. It reads the `colors.csv` dataset containing color names and RGB values.
3. When the user double-clicks on any pixel, the RGB values of that pixel are obtained.
4. The application compares these RGB values with the dataset.
5. The closest matching color name is displayed along with its RGB values.

## Sample Output

- Double-click on any part of the image.
- The detected color name appears at the top of the image.
- RGB values are displayed in the format:

```
Color Name: Vermilion (Cinnabar)
R = 234
G = 71
B = 54
```

## Learning Outcomes

- Understanding image processing using OpenCV.
- Working with RGB color space.
- Reading and processing CSV files using Pandas.
- Implementing mouse callback events.
- Building a basic computer vision application.

## Author

Bhav Gupta

Virtual Data Analytics Internship

Slash Mark
