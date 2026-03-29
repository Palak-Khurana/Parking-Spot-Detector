# 🚗 Parking-Spot-Detector

Real-time detection of free parking spots using computer vision.

This project is a smart parking detection system that uses computer vision to identify available parking spaces in real time from a video feed.

Built with Python and OpenCV, it analyzes parking lot footage and automatically highlights which spots are free and which are occupied, making parking management easier and more efficient.

## 📌 Features
✓ Real-time parking space detection  
✓ Highlights available (green) and occupied (red) slots  
✓ Counts total free spaces dynamically  
✓ Simple UI using OpenCV  
✓ Custom parking slot selection tool 

## 🧠 How It Works
### 1. The parking lot video is analyzed one frame at a time.
### 2. Several image processing techniques are applied, including:
  ➔ Converting the image to grayscale
  
  ➔ Applying Gaussian blur
  
  ➔ Using adaptive thresholding
  
  ➔ Applying median blur
  
  ➔ Performing dilation
### 3. Each parking space is then evaluated based on pixel intensity.
### 4. A lower pixel count indicates that the parking spot is available.
### 5. A higher pixel count means the spot is occupied.
### 6. The final results are displayed visually on the screen.

## 🛠️Tech Stack
• Python

• OpenCV

• NumPy

• Pickle

• CvZone

---------------------------------


## ▶️ How to Run

### 1. Clone the repository
#### git clone https://github.com/Palak-Khurana/Parking-Spot-Detector.git
#### cd Parking-Spot-Detector

### 2. Install dependencies
#### pip install opencv-python numpy cvzone

### 3. Run Parking Space Picker (first step)
#### python ParkingSpacePicker.py
#### Left click → Add parking space
#### Right click → Remove parking space

### 4. Run Main Detection
#### python main.py
