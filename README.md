
# Blind Assistant Project

An AI-powered visual assistant designed to help visually impaired users. It can read text from images, describe scenes, and detect objects using voice commands.




### 3. **Features**


## Features

- 📄 Text Reading via EasyOCR
- 🖼️ Scene Description via BLIP Model
- 🔍 Object Detection via YOLOv8
- 🔊 Text-to-Speech (TTS) Output
- 🎙️ Voice Command Interface using SpeechRecognition

### 4. **Installation**


## Installation

1. Clone this repository:



git clone [https://github.com/yourusername/Blind\_Assistant\_Project.git](https://github.com/yourusername/Blind_Assistant_Project.git)
cd Blind\_Assistant\_Project



2. Install required Python libraries:


pip install -r requirements.txt


3. Make sure **Tesseract OCR** is installed:
- Download from: https://github.com/tesseract-ocr/tesseract
- Update path in code:


pytesseract.pytesseract.tesseract\_cmd = r"C:\Program Files\Tesseract-OCR\tesseract.exe"

### 5. **How to Run (in Jupyter Notebook)**


## Usage

1. Open the notebook:



jupyter notebook Blind\_Assistant\_Project.ipynb



2. Provide full path to the image when asked:


Enter full image file path (e.g., C:\Users\khush\Pictures\image.jpg):



3. Speak a voice command:
- "text" → Reads text from image
- "scene" → Describes the scene
- "object" → Detects objects

4. The assistant will speak out the result.


### 6. **Requirements**


## Requirements

- Python 3.10+
- pytesseract
- easyocr
- ultralytics (YOLOv8)
- transformers
- torch
- torchvision
- gTTS
- SpeechRecognition
- PyAudio
- opencv-python
- Pillow
- playsound

All listed in `requirements.txt`.


---

### 7. **Notes**


## Notes

- CUDA GPU is optional but speeds up YOLO/BLIP.
- For Tesseract OCR, ensure the path is correctly set.
- Supports Windows; can be modified for Linux/Mac easily.




