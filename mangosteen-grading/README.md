#  Mangosteen Grading System
_(Automated Mangosteen Size Measurement using YOLO v11 and Hough Circle Transform)_

## 📌 Project Overview
The Mangosteen Grading System is an AI-based solution designed to measure the size of mangosteens automatically. It integrates YOLO v11 for fruit segmentation and the Hough Circle Transform to identify a reference object for accurate size calibration.

## 📅 Project Status: In Development (Planning Phase)
✅ Defining project objectives and scope
✅ Researching existing fruit grading systems
✅ Choosing suitable deep learning models (YOLO v11) and image processing techniques (Hough Transform)
🔄 Developing dataset collection strategy
🔄 Prototyping initial detection models

## 🏆 Key Features
- **Deep Learning for Object Detection:** Utilizes YOLO v11 to detect mangosteens in images.
- **Size Calibration:** Uses the Hough Circle Transform to detect a reference circle (1 cm) and convert pixel measurements to real-world units.
- **Automated Image Processing:** Processes images of mangosteens on a white background to compute their diameters.
- **Optimized for Efficiency:** Reduces manual measurement errors and enhances the grading process.

## 🔧 Technologies Used
- Python
- YOLO v11
- OpenCV (Image processing & Hough Circle Transform)
- Google Colab (GPU acceleration for training)
- Matplotlib & NumPy (Data visualization and calculations)

## Next Steps
🔹 Complete dataset collection (gather high-quality mangosteen images)
🔹 Develop initial object detection model using YOLO v11
🔹 Test different approaches for size calibration (Hough Transform vs. other methods)
🔹 Evaluate initial prototype performance

## 📊 Expected Outcomes
✅ A robust mangosteen detection and grading system
✅ Reduced manual grading errors
✅ Optimized fruit grading workflow for the industry
