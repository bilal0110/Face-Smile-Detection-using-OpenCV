# Face-Smile-Detection-using-OpenCV

## 📌 Project Overview
This project detects **faces, eyes, and smiles in real-time** using a webcam.  
It uses **Haar Cascade Classifiers** from OpenCV to identify facial features and display results live.

---

## 🎯 Objective
To build a real-time computer vision system that can:

- Detect human faces  
- Detect eyes  
- Detect smiles  
- Display a message when a smile is detected  

---

## 🧠 How It Works

The project uses pre-trained Haar cascade models:

- `haarcascade_frontalface_default.xml` → Face detection  
- `haarcascade_eye.xml` → Eye detection  
- `haarcascade_smile.xml` → Smile detection  

### Workflow:
1. Capture video from webcam  
2. Convert frame to grayscale  
3. Detect faces  
4. Detect eyes inside face region  
5. Detect smiles inside face region  
6. Display result on screen  

---

## ⚙️ Features

- Real-time webcam detection  
- Face, eye, and smile detection  
- Live bounding boxes around features  
- Displays:
  - 😊 "Smile Detected!"  
  - "No Smile"  

---

## 🛠️ Tech Stack

- Python  
- OpenCV (cv2)  

