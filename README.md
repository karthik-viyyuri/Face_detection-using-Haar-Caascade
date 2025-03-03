# Face Recognition Using AI and ML

This repository contains a face recognition system built using **OpenCV, NumPy, and machine learning techniques**. The project covers the full pipeline from **face dataset collection, model training, and real-time face recognition**.

## 🚀 Features
- **Face Detection**: Uses OpenCV’s Haar cascade classifier.
- **Dataset Creation**: Captures and stores face images.
- **Model Training**: Trains a face recognition model using the dataset.
- **Real-time Recognition**: Identifies faces from a live video feed.

## 📂 Project Structure
- **`1_face_dataset.py`** – Captures and stores face images.
- **`2_face_training.py`** – Trains the recognition model using the dataset.
- **`3_face_recognition.py`** – Runs real-time face recognition.
- **`haarcascade_frontalface_default.xml`** – Pre-trained Haar cascade classifier for face detection.

## 🏗️ Installation & Setup
### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/face-recognition.git
cd face-recognition
```

### 2️⃣ Create a virtual environment (Optional but recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

### 3️⃣ Install dependencies
```bash
pip install opencv-python numpy
```
### NOTE: create a file named "datasets" before running as the program, to store the face data.
### 4️⃣ Run the Project
#### Collect Face Data
```bash
python 1_face_dataset.py
```
This script captures images and stores them in the dataset.

#### Train the Model
```bash
python 2_face_training.py
```
This trains the face recognition model.

#### Recognize Faces
```bash
python 3_face_recognition.py
```
This detects and recognizes faces in real time.

## 🛠️ Tech Stack
- **Python 3.x** – Programming language
- **OpenCV** – Computer vision library
- **NumPy** – Numerical computations

## 🤝 Contributing
Contributions are welcome! Feel free to submit **issues** or **pull requests** to improve this repository.

## 📜 License
This project is licensed under the **MIT License**.

## 📬 Contact
For any questions, feel free to reach out:
- **Email:** karthikviyyuri@gmail.com
- **LinkedIn:** [Karthik Viyyuri](https://www.linkedin.com/in/karthik-viyyuri-b13248259/)
