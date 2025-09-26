# Car Plate Character Recognition

## Description

This project demonstrates an image processing pipeline designed to enhance and recognize characters on vehicle license plates. The steps include:

1. **Edge Enhancement**: The Laplacian filter sharpens the plate characters to make them clearer.
2. **Gaussian Low-Pass Filtering**: Applied in the frequency domain to blur the background and highlight the license plate characters.
3. **Thresholding and Masking**: Used to isolate the characters from the background for further analysis.
4. **OCR**: `pytesseract` is used to extract text from the processed license plate image.

## Requirements

- Python 3.x
- OpenCV
- NumPy
- Matplotlib
- pytesseract

Install required packages using:

```bash
pip install opencv-python matplotlib numpy pytesseract
```

## Files

- **car.jpg**: The input image of a car plate.
- **Processed images**: Outputs after applying image enhancement, masking, and thresholding.

## How to Use

1. Run the notebook `Car_Plate_Character_Recognition.ipynb` in a Jupyter environment.
2. The notebook will load the image, apply various image processing techniques, and extract text from the license plate using OCR.


