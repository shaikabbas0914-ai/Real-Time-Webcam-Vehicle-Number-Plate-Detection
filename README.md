# 🚗 Indian Vehicle Number Plate Detection & Recognition System (ANPR)

## 🔥 AI-Powered Indian Automatic Number Plate Recognition System

Detect • Recognize • Validate • Track Indian Vehicle Number Plates in Real-Time

---

# 📌 Overview

This project is an AI-based **Automatic Number Plate Recognition (ANPR)** system designed specifically for **Indian Vehicles** using:

- YOLOv8
- OpenCV
- EasyOCR
- Python

The system can:

✅ Detect vehicle number plates  
✅ Extract plate text using OCR  
✅ Validate Indian registration formats  
✅ Process webcam/video/image inputs  
✅ Work in real-time  

---

# 🎯 Features

✨ Real-time webcam detection  
✨ Image & video processing  
✨ OCR-based text extraction  
✨ Indian number plate validation  
✨ YOLOv8 deep learning detection  
✨ Automatic plate image saving  
✨ Confidence score display  
✨ Google Colab support  
✨ Easy-to-use architecture  

---

# 🧠 Tech Stack

| Technology | Purpose |
|------------|----------|
| 🐍 Python | Core Programming |
| YOLOv8 | Object Detection |
| OpenCV | Image Processing |
| EasyOCR | OCR Text Recognition |
| NumPy | Numerical Computation |
| Matplotlib | Visualization |

---

# 🏗️ System Architecture

```text
Input Image / Webcam / Video
              │
              ▼
     YOLOv8 Number Plate Detection
              │
              ▼
        Plate Cropping
              │
              ▼
      Image Preprocessing
              │
              ▼
       OCR Text Extraction
              │
              ▼
   Indian Number Validation
              │
              ▼
       Display Final Output
```

---

# 📂 Project Structure

```text
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
├── outputs/
│
├── main.py
├── requirements.txt
└── README.md
```

---

# ⚙️ Installation

## 🔹 Step 1 — Clone Repository

```bash
git clone https://github.com/your-username/Indian_ANPR.git
cd Indian_ANPR
```

---

## 🔹 Step 2 — Create Virtual Environment

### 🪟 Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### 🐧 Linux / Mac

```bash
python3 -m venv venv
source venv/bin/activate
```

---

## 🔹 Step 3 — Install Dependencies

```bash
pip install -r requirements.txt
```

OR manually:

```bash
pip install ultralytics
pip install opencv-python
pip install easyocr
pip install numpy
pip install matplotlib
```

---

# ▶️ Running the Application

```bash
python main.py
```

📌 Press:

```text
ESC
```

to stop webcam detection.

---

# 📸 Input Sources Supported

✅ Webcam  
✅ CCTV Feed  
✅ Video Files  
✅ Image Uploads  

---

# 🔍 OCR Workflow

```text
Detect Plate
    ↓
Crop Plate Region
    ↓
Convert to Grayscale
    ↓
Apply Thresholding
    ↓
Extract Text using OCR
    ↓
Validate Indian Number Format
```

---

# 🇮🇳 Indian Number Plate Validation

## Supported Formats

```text
TS09AB1234
MH12DE1433
DL01XY0001
```

## Regex Used

```python
^[A-Z]{2}[0-9]{1,2}[A-Z]{1,2}[0-9]{4}$
```

---

# 🖼️ Sample Output

```text
Detected Plate: TS09AB1234
Confidence: 0.94
Status: Valid Indian Number Plate
```

---

# 📦 requirements.txt

```txt
ultralytics
opencv-python
easyocr
numpy
matplotlib
torch
torchvision
```

---

# ☁️ Google Colab Support

Install dependencies in Colab:

```python
!pip install ultralytics
!pip install easyocr
!pip install opencv-python-headless
```

---

# 🚀 Future Enhancements

✅ PaddleOCR integration  
✅ FastAPI backend  
✅ React dashboard  
✅ Database logging  
✅ Multi-camera support  
✅ Helmet detection  
✅ Vehicle tracking  
✅ Speed estimation  
✅ Cloud deployment  

---

# 📊 Applications

🚦 Traffic Monitoring  
🅿️ Smart Parking  
🏫 Campus Entry Systems  
💳 Toll Collection  
🚔 Security Surveillance  
📸 Automatic Challan Systems  
🚘 Vehicle Tracking  

---

# ⚠️ Limitations

⚠️ OCR accuracy depends on image quality  
⚠️ Night-time images may reduce performance  
⚠️ Dirty or blurred plates affect OCR  
⚠️ Pretrained models may require fine-tuning  

---

# 🧠 Learning Outcomes

By completing this project, you will learn:

✅ Computer Vision  
✅ Object Detection  
✅ OCR Systems  
✅ Deep Learning  
✅ OpenCV  
✅ YOLOv8  
✅ Real-time AI Applications  

---

# 👨‍💻 Author

Developed with ❤️ using Python, YOLOv8, OpenCV & EasyOCR

---

# 🌟 Show Your Support

If you like this project:

⭐ Star the repository  
🍴 Fork the project  
📢 Share with others  

---

# 📚 Useful Resources

- https://docs.ultralytics.com
- https://docs.opencv.org
- https://github.com/JaidedAI/EasyOCR
- https://www.python.org

---

# 🚀 AI + Computer Vision + OCR = Smart Vehicle Intelligence
