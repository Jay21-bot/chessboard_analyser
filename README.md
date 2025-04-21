# Chessboard Analysis with Computer Vision 🧩

## 🚀 Project Overview
This project uses **Computer Vision** to analyze chessboard images, counting the number of black and white squares. It is designed to handle various challenges, including different orientations, lighting variations, and image imperfections. The solution leverages **OpenCV** for image processing and **NumPy** for numerical operations.

## 🔧 Key Features
- **Image Preprocessing**: Converts images to grayscale, applies Gaussian blur, and uses Otsu's thresholding to clearly distinguish black and white squares.
- **Square Detection**: Uses contour detection to locate and classify each square as either black or white based on pixel intensity.
- **Dynamic Handling**: Robust to different chessboard orientations, lighting changes, and distortions in the image.

## 🧰 Libraries Used
- **OpenCV**: For core image processing tasks (e.g., grayscale conversion, thresholding, contour detection).
- **NumPy**: For array manipulation and numerical operations.

## 📸 How to Use
### 1. Upload Chessboard Images
Upload your own chessboard images to the Colab environment. Make sure to test with at least two images to see how the system handles different orientations or lighting.

### 2. Run the Code
Execute the notebook cells sequentially. Each step processes the images, detects squares, and classifies them as black or white.

### 3. View Results
The notebook will display:
- Annotated images with detected squares.
- The count of black and white squares.

## 💻 Example Output
Once the analysis is complete, the output will look something like this:
