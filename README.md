# Low-Light License Plate Recognition Using Deep Learning

This project presents a deep learning pipeline for Automatic License Plate Recognition (ALPR) in low-light conditions using Zero-DCE for image enhancement, YOLOv8 for vehicle and number plate detection, and TrOCR for character recognition.

---

## 📌 Project Description

This research project aims to solve the problem of license plate recognition under low-light conditions, which is common in real-world surveillance and traffic monitoring systems. We use a modular deep learning pipeline that enhances image quality, detects vehicles and license plates, and accurately extracts plate numbers—even in poor visibility scenarios.

### ✨ Key Features

- **Image Enhancement**:  
  Uses **Zero-DCE**, a model that learns pixel-wise curves to improve brightness and contrast without needing paired data. It helps preserve license plate details even in very dark images.

- **Vehicle & Plate Detection**:  
  Uses **YOLOv8**, the latest iteration of the YOLO object detection model, to localize vehicles and number plates with high accuracy and fast inference.

- **Character Recognition**:  
  Uses **TrOCR**, a transformer-based OCR model, for recognizing license plate numbers. It performs well even with blurry, angled, or low-resolution text.

### 💡 Technologies Used

- YOLOv8 (Ultralytics)
- Zero-DCE (TensorFlow)
- TrOCR (Hugging Face Transformers)
- Python
- PyTorch
- OpenCV

### 🔍 Challenges Faced

- Enhancing low-light images without overexposing brighter regions.
- Detecting number plates in vehicles under varying lighting and angles.
- Training OCR models for non-standard fonts and local (Sri Lankan) plate formats.

### 🚀 Future Improvements

- Real-time deployment on edge devices like Jetson Nano or Raspberry Pi.
- Expand dataset to include multi-language number plates.
- Add motion blur removal for clearer recognition.

---

## 📁 Datasets Used

- **Low-Light Image Dataset**  
  `Used to train and evaluate Zero-DCE model for image enhancement`  
  [Download Here](https://drive.google.com/drive/folders/1YMd7tswD_MJKotp_ILtQ2X8kmnoIIOF6?usp=sharing)

- **Sri Lankan Number Plate Dataset**  
  `Used to train YOLOv8 model for detecting number plates and vehicles`  
  [Download Here](https://drive.google.com/drive/folders/1Nx4cMnA59Vl2oIwgsbiC_PteE__M4xit?usp=sharing)

---

## 🧠 Pretrained Models

> **Note**: These models are shared for academic purposes. If you would like to use them, please request access through the links below.

- **Zero-DCE Low-Light Enhancement Model**  
  [Access Model](https://drive.google.com/file/d/1QIb50-roo5CDY1OIrsNW0MVGhSw5up53/view?usp=sharing)

- **YOLOv8 Vehicle & Plate Detection Model**  
  [Access Model](https://drive.google.com/file/d/1QIb50-roo5CDY1OIrsNW0MVGhSw5up53/view?usp=sharing)

---

## 📬 Request for Access

If you are interested in using the pretrained models or datasets for academic or research purposes, please request access via the shared Google Drive links. Mention your intended use in the request.

---


## 🙌 Acknowledgements

- Ultralytics for YOLOv8
- Microsoft Research for TrOCR
- Zero-DCE authors for open-source model
- Contributors to open Sri Lankan license plate datasets
