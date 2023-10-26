# Face Detection Multi-Image Repository

## Overview

This repository contains a Python script for detecting and highlighting faces in multiple images using the OpenCV library. The script utilizes the Haar Cascade Classifier to identify faces within the provided images.

## Requirements

Before using this script, make sure you have the following prerequisites installed on your system:

- Python (3.x recommended)
- OpenCV (cv2)
- A collection of images for face detection

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/shakeebparwez/face-detection-multi-image.git
   ```

2. Navigate to the repository directory:

   ```bash
   cd face-detection-multi-image
   ```

3. Install the required Python libraries:

   ```bash
   pip install opencv-python
   ```

## Usage

1. Place the images you want to process in the `multi-image-detector` directory.

2. Run the `face_detector.py` script:

   ```bash
   python face_detector.py
   ```

3. The script will process each image, detect faces, and display the images with highlighted faces for 2 seconds each.

4. Press any key to close the displayed image and proceed to the next one.

## Customization

- You can adjust the detection parameters like the scale factor and minimum neighbors in the `detect.detectMultiScale` method for more accurate results.

- Customize the color and line thickness of the rectangle used to highlight faces by modifying the arguments in the `cv2.rectangle` function.

## Example

Here is an example of how the script works:

![Face Detection Example](screenshot.png)

## Contribution

If you find any issues or want to enhance the functionality of this script, feel free to fork the repository and create a pull request.

## Author

- Shakeeb Parwez
- Contact: shakeebparwez@gmail.com
