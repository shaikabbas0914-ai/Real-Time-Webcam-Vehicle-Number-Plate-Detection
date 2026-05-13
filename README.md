Indian Vehicle Number Plate Detection System
AI-Based Automatic Number Plate Recognition (ANPR) for Indian Vehicles
📌 Project Overview

This project is an AI-powered Indian Vehicle Number Plate Detection & Recognition System built using:

YOLOv8
OpenCV
EasyOCR
Python

The system detects vehicle number plates from:

Images
Videos
Real-time webcam streams

and extracts the vehicle registration number using OCR.

🚀 Features

✅ Real-time webcam detection
✅ Vehicle number plate detection
✅ OCR text extraction
✅ Indian number plate validation
✅ Confidence score display
✅ Automatic plate image saving
✅ OpenCV visualization
✅ Google Colab support
✅ YOLOv8 deep learning integration

🧠 Technologies Used
Technology	Purpose
Python	Core Programming
YOLOv8	Number Plate Detection
OpenCV	Image Processing
EasyOCR	Text Recognition
NumPy	Numerical Operations
Matplotlib	Visualization
Regex	Indian Plate Validation
📂 Project Structure
Indian_ANPR/
│
├── models/
│   └── best.pt
│
├── detected_plates/
│
├── images/
│
├── videos/
│
├── main.py
├── requirements.txt
└── README.md
⚙️ Installation
Step 1 — Clone Repository
git clone <your-repository-link>
cd Indian_ANPR
Step 2 — Create Virtual Environment
Windows
python -m venv venv
venv\Scripts\activate
Linux/Mac
python3 -m venv venv
source venv/bin/activate
Step 3 — Install Dependencies
pip install ultralytics
pip install opencv-python
pip install easyocr
pip install matplotlib
pip install numpy

OR

pip install -r requirements.txt
▶️ Run the Application
python main.py

Press:

ESC

to exit webcam detection.

🖼️ Input Sources

The system supports:

Webcam
CCTV Feed
Video File
Image Upload
📸 Webcam Detection Workflow
Webcam → YOLOv8 Detection → Plate Crop →
Preprocessing → OCR → Validation → Display
🔍 OCR Workflow
Detect Number Plate
Crop Plate Region
Convert to Grayscale
Apply Thresholding
Extract Text using OCR
Validate Indian Plate Format
🇮🇳 Indian Number Plate Validation

Supported format:

TS09AB1234
MH12DE1433
DL01XY0001

Regex Used:

^[A-Z]{2}[0-9]{1,2}[A-Z]{1,2}[0-9]{4}$
🧪 Sample Output
Detected Plate: TS09AB1234
Confidence: 0.94
Valid Indian Number Plate
📦 requirements.txt
ultralytics
opencv-python
easyocr
numpy
matplotlib
torch
torchvision
🖥️ Google Colab Support

This project can also run on:

Google Colab

Install dependencies in Colab:

!pip install ultralytics
!pip install easyocr
!pip install opencv-python-headless
📊 System Architecture
Input Image/Video/Webcam
          ↓
YOLOv8 Number Plate Detection
          ↓
Plate Cropping
          ↓
Image Preprocessing
          ↓
EasyOCR Text Recognition
          ↓
Regex Validation
          ↓
Display & Save Results
📈 Future Improvements

✅ PaddleOCR integration
✅ FastAPI backend
✅ React dashboard
✅ Database logging
✅ Multi-camera support
✅ Helmet detection
✅ Vehicle tracking
✅ Speed estimation
✅ Cloud deployment

🔥 Recommended Upgrades
Upgrade	Technology
Better OCR	PaddleOCR
Web API	FastAPI
Dashboard	React
Deployment	Docker
📌 Applications
Smart Parking
Traffic Monitoring
Toll Collection
Vehicle Tracking
Security Surveillance
Automatic Challan System
Campus Entry Systems
⚠️ Limitations
OCR accuracy depends on image quality
Night-time detection may reduce performance
Dirty/blurred plates affect OCR accuracy
Pretrained model may need fine-tuning
🧠 Learning Outcomes

By completing this project, you will learn:

Computer Vision
Object Detection
OCR Systems
Deep Learning
OpenCV
YOLOv8
Real-time AI systems
👨‍💻 Author
Developed using Python, YOLOv8, OpenCV, and EasyOCR
📚 Useful Resources
Ultralytics YOLO Documentation
OpenCV Official Documentation
EasyOCR GitHub Repository
Python Official Website
⭐ If You Like This Project
Star ⭐ the repository and contribute to improve the project.