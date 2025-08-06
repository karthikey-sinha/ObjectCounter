# Count Objects in Image

This project demonstrates how to **detect and count objects** in an image using **Python, OpenCV, and NumPy**.
It applies common computer vision techniques like grayscale conversion, Gaussian blurring, edge detection (Canny), and contour detection.

## Features

* Read and display images.
* Convert images to grayscale.
* Apply Gaussian blur to reduce noise.
* Detect edges using the Canny edge detector.
* Dilate edges to strengthen contours.
* Find and count distinct objects.
* Draw contours around detected objects.

## Example Outputs

* Count bottles in an image.
* Count coins in an image.

## Tech Stack

* **Python 3.x**
* **OpenCV** for image processing.
* **NumPy** for numerical operations.
* **Matplotlib** for visualization.

## Installation

```bash
pip install opencv-python numpy matplotlib
```

## Usage

1. Place your target image (`bottles.jpg`, `coins.jpg`, etc.) in the same directory.
2. Open and run the Jupyter Notebook:

```bash
jupyter notebook countObjectsInImage.ipynb
```

3. The notebook will:

   * Display intermediate processing steps.
   * Show the number of detected objects.

## How It Works

1. **Read Image** → Load the target image using `cv2.imread()`.
2. **Preprocessing** → Convert to grayscale and apply Gaussian blur.
3. **Edge Detection** → Use Canny edge detection to find object boundaries.
4. **Dilation** → Make edges more prominent for contour detection.
5. **Find Contours** → Detect and count objects with `cv2.findContours()`.
6. **Visualization** → Draw contours and print object count.

## Sample Output

```
Number of objects in the image: 7
```

*(with an image showing the objects outlined in green)*

## Author

Karthikey Sinha

---

If you want, I can also **add example images** and a **flow diagram** to make the README more attractive for GitHub. That would give it a professional, portfolio-ready look.
