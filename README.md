# Image Encoding and Decoding Project

This project is part of the DMET 501 course at the German University in Cairo, Faculty of Media Engineering and Technology. The project involves implementing an encoding and decoding technique on an image using Python and OpenCV.

## Project Details

- Course: DMET 501 - Introduction to Media Engineering
- Semester: Winter 2023

## Getting Started

To get started with the project, follow the instructions below.

### Prerequisites

- Python 
- OpenCV

### Installation

1. Clone the repository
2. Install the required dependencies
    * `pip install opencv-python`

### Project Structure

The project contains the following files:

- `main.ipynb`: Python notebook containing the implementation code.
- `house.tif`: Input image file.

### Usage

1. Open the `main.ipynb` notebook in Jupyter or any other compatible environment.
2. Run the notebook cells to execute the code.
3. Modify the code in the designated areas to complete the required tasks.
4. Test your code using the provided test cells.
5. Submit your completed code.

### Tasks

The project consists of two parts: encoding and decoding.

#### Part 1: Encoding

- Task 1: Convert the image from grayscale to binary.
- Task 2: Get the starting indices of ones in a specific row.
- Task 3: Get the lengths of consecutive runs of ones in a specific row.
- Task 4: Encode the image into a string representation.

#### Part 2: Decoding

- Task 1: Split the encoded string by row number.
- Task 2: Decode a single row.
- Task 3: Reconstruct the binary image from the encoded string.

## Resources

- [OpenCV Documentation](https://docs.opencv.org/)
- [Python Documentation](https://docs.python.org/)