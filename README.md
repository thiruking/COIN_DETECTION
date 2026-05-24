# Coin Detection using OpenCV

## Aim

To detect and count the number of coins present in an image using Python and OpenCV.

---

## Objective

The objective of this experiment is to perform image preprocessing and blob detection techniques to identify and count coins from an input image.

---

## Software Required

- Python 3.x
- OpenCV (`cv2`)
- NumPy
- Matplotlib
- Jupyter Notebook / VS Code

---

## Theory

Coin detection is an image processing application used to identify circular objects from an image. 

The process involves:

- Converting the image into grayscale
- Applying thresholding
- Performing morphological operations
- Detecting blobs using SimpleBlobDetector

Blob detection helps identify connected regions in an image that differ in brightness or color properties.

---

## Algorithm

### Step 1:
Import the required libraries such as OpenCV, NumPy, and Matplotlib.

### Step 2:
Read the input image using `cv2.imread()`.

### Step 3:
Convert the image into grayscale using `cv2.cvtColor()`.

### Step 4:
Split the image into Red, Green, and Blue channels.

### Step 5:
Apply thresholding using `cv2.threshold()` to separate foreground objects from the background.

### Step 6:
Perform median filtering to reduce noise.

### Step 7:
Apply dilation and erosion operations using morphological techniques.

### Step 8:
Configure the SimpleBlobDetector parameters.

### Step 9:
Detect blobs (coins) using `detector.detect()`.

### Step 10:
Display the detected coins and print the number of coins detected.

---

## OpenCV Functions Used

| Function | Purpose |
|---|---|
| `cv2.imread()` | Read image |
| `cv2.cvtColor()` | Convert image color space |
| `cv2.threshold()` | Apply thresholding |
| `cv2.medianBlur()` | Remove noise |
| `cv2.dilate()` | Perform dilation |
| `cv2.erode()` | Perform erosion |
| `cv2.SimpleBlobDetector()` | Detect blobs |
| `cv2.drawKeypoints()` | Draw detected blobs |

---

## Expected Output

The program produces the following outputs:

- Original Image
- Grayscale Image
- Thresholded Image
- Dilated Image
- Eroded Image
- Detected Coins Output
- Number of Coins Detected

---

## Applications

- Object counting systems
- Currency recognition
- Industrial automation
- Shape detection
- Computer vision applications
- Image analysis systems

---

## Result

Thus, the coins present in the image are successfully detected and counted using Python and OpenCV.

---

## Developed By

**Name:** ____________________________

**Register Number:** ____________________________
