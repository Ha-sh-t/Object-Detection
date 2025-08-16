# Object-Detection

# 🖐️ Sign Language Detection using YOLO

This project implements **Sign Language Detection** using the **YOLO (You Only Look Once)** object detection model.  
The system can detect and classify different sign language gestures from collected images and real-time video streams.

---

## 📂 Project Structure

├── CollectedImages/ # Collected dataset images
|
├── data/ # Raw & processed data
├── signLanguage/ # Main project package
│ ├── components/ # Core modules
│ │ ├── data_ingestion.py # Data loading pipeline
│ │ ├── data_validation.py # Data validation
│ │ ├── model_trainer.py # Training YOLO model
│ │ ├── model_pusher.py # Model deployment
│ ├── configuration/ # Configuration & S3 operations
│ ├── constant/ # Project constants
│ ├── entity/ # Entity classes (config, artifacts)
│ ├── exception/ # Custom exception handling
│ ├── logger/ # Logging utility
│ ├── pipeline/ # End-to-end training & inference pipelines
│ ├── utils/ # Utility functions
├── template/ # Project templates
├── app.py # Flask app for inference
├── data_collector.py # Script to collect images
├── requirements.txt # Python dependencies
├── setup.py # Installable package setup
├── Dockerfile # Docker support
├── .gitignore # Git ignore rules
└── README.md # Project documentation

---

## 🚀 Features

- Collect sign language gesture images.
- Preprocess and validate dataset.
- Train YOLO-based object detection model.
- Deploy model with Flask API.
- Docker support for containerized deployment.
- AWS S3 integration for storing models & artifacts.

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/sign-language-detection.git
cd sign-language-detection
```
