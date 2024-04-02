# Real-time-image-to-text
## Webcam Text Detection with EasyOCR

This project demonstrates how to capture an image using the webcam in Google Colab and perform text detection on the captured image using EasyOCR and OpenCV. The detected text is annotated on the image and displayed.

## Dependencies

This project requires the following dependencies:

- `cv2`: OpenCV library for image processing.
- `easyocr`: EasyOCR library for text detection.
- `matplotlib`: Matplotlib library for visualization.
- `numpy`: NumPy library for numerical computations.
- `IPython`: IPython library for displaying images and executing JavaScript code in Colab.

To install the dependencies, you can use the following command:

```bash
!pip install opencv-python-headless easyocr matplotlib numpy
```
## Usage

To use this project, follow these steps:

1. Open the provided Python script in Google Colab.
2. Run each cell in the notebook sequentially.
3. When prompted, grant permission to access the webcam to capture an image.
4. The captured image will be displayed along with the detected text annotations.

## Code Overview

The project consists of the following components:

1. `detect_text(image)`: This function takes an image as input, performs text detection using EasyOCR, and annotates the detected text on the image using bounding boxes. It then displays the annotated image using Matplotlib.

2. `take_photo_and_detect_text(filename='photo.jpg', quality=0.8)`: This function captures an image using the webcam in Google Colab, saves it to a file specified by the `filename` parameter, and then calls the `detect_text` function to perform text detection on the captured image.

3. Main execution: The main block of code calls the `take_photo_and_detect_text` function to capture an image and perform text detection.

## Demo Video

[Link to demo video](https://github.com/rajrawal/Real-time-image-to-text/assets/119045146/3690e00c-0660-48f1-93d0-eee7808372c8)

## Captured Image
![img1](https://github.com/rajrawal/Real-time-image-to-text/assets/119045146/43e5a7c5-5a4e-4032-895a-1b81cd700726)
### After Text Detection
![img1](https://github.com/rajrawal/Real-time-image-to-text/assets/119045146/8932dfe3-4f3a-4fde-9e1b-428c843ab704)


