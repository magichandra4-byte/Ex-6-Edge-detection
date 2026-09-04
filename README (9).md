# edge-detection-opencv

## Aim
To perform edge detection using Sobel, Roberts, Prewitt, Laplacian, and Canny edge detectors.

---

## Software Required
1. Anaconda – Python 3.7
2. Jupyter Notebook / VS Code
3. OpenCV (cv2)
4. NumPy
5. Matplotlib

---

## ⚙️ Algorithm
### Step 1:
Import all the necessary modules for the program.

### Step 2:
Load an image using cv2.imread().

### Step 3:
Convert the image to grayscale.

### Step 4:
Apply Sobel operator using OpenCV to detect edges.

### Step 5:
Apply Prewitt operator using custom kernels.

### Step 6:
Apply Roberts operator using custom kernels.

### Step 7:
Apply Laplacian operator using OpenCV.

### Step 8:
Apply Canny edge detector using OpenCV.

### Step 9:
Display all edge-detected images for comparison.

---

## Developed By
1. Name: ____________________________
2. Register No: ______________________

---

## Output
### Sobel Edge Detector
1. Detects edges in horizontal and vertical directions
2. Produces gradient-based edge map
### Prewitt Edge Detector
1. Similar to Sobel but simpler kernel
2. Detects directional edges
### Roberts Edge Detector
1. Detects edges using diagonal gradients
2. Sensitive to noise
### Laplacian Edge Detector
1. Detects edges using second-order derivatives
2. Highlights rapid intensity changes
### Canny Edge Detector
1. Multi-stage edge detection
2. Produces clean and thin edges

# Result
Thus, edges are successfully detected using Sobel, Prewitt, Roberts, Laplacian, and Canny edge detection techniques. Each method highlights edges differently based on gradient and intensity variations, improving feature extraction and analysis.
