# Image Processing Application using PyQt5 and OpenCV

## Overview
This is a simple image-processing application developed using PyQt5 and OpenCV. The application provides a graphical user interface (GUI) for loading, processing, and saving images. It offers a variety of image processing operations, such as rotation, filtering, edge detection, and more.

## Features
- **File Operations:**
  - Open an image file.
  - Save the current image.

- **Image Operations:**
  - Resize the image (enlarge or shrink).
  - Apply various image processing techniques like rotation, shearing, translation, etc.

- **Image Enhancement:**
  - Convert the image to grayscale.
  - Apply negative transformation.
  - Perform histogram equalization.
  - Apply logarithmic and gamma corrections.

- **Image Restoration:**
  - Add different types of noise to the image.
  - Perform histogram analysis.
  - Implement various image restoration techniques like Wiener, median, and adaptive median filtering.

- **Edge Detection:**
  - Apply simple edge detection using the Canny edge detector.
  - Implement the Hough Transform for line detection.

- **Smoothing:**
  - Apply various smoothing filters like blur, box, median, bilateral, and Gaussian filters.

- **Filtering:**
  - Implement median thresholding.
  - Apply directional filtering.
  - Implement Butterworth and notch filters.

- **Cartoon Effect:**
  - Create a cartoon effect by combining bilateral filtering and edge detection.

## How to Use
1. Run the script using a Python interpreter.
2. The application window will appear with a menu bar and various image processing options.
3. Use the "Open File" option to load an image.
4. Perform desired image processing operations using the menu options.
5. Save the processed image using the "Save File" option.

## Dependencies
- PyQt5
- OpenCV
- NumPy
- SciPy
- Matplotlib

## Author
- Argha Kamal Samanta

## Notes
- Make sure to have the required dependencies installed before running the application.
- The application provides a graphical user interface, making it user-friendly for image processing tasks.
- Feel free to explore and modify the code to add more functionalities or customize the user interface.
