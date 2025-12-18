##🚗 Automatic License Plate Recognition (ALPR)

An **Automatic License Plate Recognition (ALPR)** system built using **Computer Vision and Machine Learning** techniques. This project detects vehicle license plates from images and extracts the plate number using OCR.

---

## 📌 Project Overview

Automatic License Plate Recognition (ALPR) is widely used in:

* Traffic monitoring
* Toll collection systems
* Parking management
* Law enforcement

This notebook demonstrates a **complete ALPR pipeline**, from image preprocessing to text extraction.

---

## 🧠 Key Features

* Vehicle image preprocessing
* License plate detection using computer vision
* Character segmentation
* Optical Character Recognition (OCR)
* End-to-end pipeline in a single notebook
* Used Google T4 GPU with 2-step Fine Tuning
---

## 🛠️ Tech Stack

* **Python**
* **OpenCV** – image processing
* **NumPy** – numerical operations
* **Matplotlib** – visualization
* **Pytesseract / OCR** – text extraction
* **Google Colab** – development environment

---

## 📂 Repository Structure

```
License-Plate-Recognition/
│
├── ALPR.ipynb        # Main Colab notebook
├── README.md        # Project documentation
```

---

## ▶️ How to Run

### Option 1: Run on Google Colab (Recommended)

1. Open the notebook in Google Colab
2. Run all cells sequentially
3. Upload a vehicle image when prompted

### Option 2: Run Locally

```bash
pip install opencv-python numpy matplotlib pytesseract
```

Then open and run the notebook using Jupyter Notebook or VS Code.

---

## 📊 Sample Workflow

1. Input vehicle image
2. Convert image to grayscale
3. Apply noise reduction & edge detection
4. Detect license plate region
5. Extract text using OCR

---

## 📈 Results

* Successfully detects license plates from clear vehicle images
* OCR accuracy depends on image quality and lighting conditions

---

## 🚀 Future Improvements

* Use a physical system with a better GPU for faster training and inference
* Train models for more epochs to improve detection and OCR accuracy
* Add vehicle type detection (car, bike, truck, bus, etc.) along with license plate recognition
* Improve accuracy for low-quality images
* Real-time video-based ALPR
* Multi-country license plate support

---

## 👨‍💻 Author

**Tanish Sharma**
B.Tech – AI & ML
NIT Kurukshetra

---

## ⭐ Acknowledgements
- This project was inspired by the research paper:
  **“A Deep Learning-Based System for Automatic License Plate Recognition Using YOLOv12 and PaddleOCR”**,  
  *Applied Sciences, MDPI*.  
  https://www.mdpi.com/3400936
- OpenCV documentation
- Google Colab



---

## 📜 License

This project is open-source and available under the **MIT License**.

---

⭐ If you find this project useful, consider giving it a star!
