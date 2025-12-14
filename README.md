# AI Deepfake Detection Web Application 🧠🖼️

## 📌 Project Overview

The **AI Deepfake Detection Web Application** is a **Flask-based machine learning web app** that detects whether an uploaded image is **Real or Deepfake** using a trained deep learning model.

Users can upload an image through a simple web interface, and the system analyzes the image using a backend prediction model to return the **prediction result along with confidence score**.

This project demonstrates **AI integration with web development**, model inference, file handling, and end-to-end deployment logic.

---

## 🎯 Features

* Web-based image upload interface
* Secure file handling for uploaded images
* Deepfake image classification (Real / Fake)
* Confidence score display
* Clean UI with Home, About, and Logout pages
* Flask backend integration with ML model

---

## 🛠️ Technologies Used

* **Programming Language:** Python
* **Web Framework:** Flask
* **Machine Learning:** PyTorch (Model Inference)
* **Frontend:** HTML, CSS, Jinja2
* **File Handling:** Werkzeug
* **IDE:** PyCharm / VS Code

---

## 🧠 Machine Learning Workflow

1. User uploads an image
2. Image is securely saved on the server
3. Image path is passed to the prediction function
4. Deep learning model analyzes the image
5. Prediction result and confidence score are returned
6. Output is displayed on the web interface

---

## ▶️ How to Run the Project

### 🔹 Prerequisites

* Python **3.8 – 3.10** (Recommended)
* Flask
* PyTorch
* Required ML dependencies

---

### 🔹 Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/AI-Deepfake-Detection.git
   ```
2. Navigate to the project directory:

   ```bash
   cd AI-Deepfake-Detection
   ```
3. Install required dependencies:

   ```bash
   pip install flask torch torchvision torchaudio opencv-python numpy
   ```
4. Run the Flask application:

   ```bash
   python app.py
   ```
5. Open browser and visit:

   ```
   http://127.0.0.1:5000/
   ```

---

## 🔐 Security & File Handling

* Uploaded files are validated and securely stored
* Filenames are sanitized using `secure_filename`
* Upload directory is auto-created if not present

---

## 🚀 Future Enhancements

* Video deepfake detection
* Live webcam analysis
* Improved UI with drag-and-drop upload
* Model optimization for faster inference
* Cloud deployment (AWS / Render / Railway)

---

## 🎤 Interview Relevance

This project demonstrates:

* AI + Web integration
* Model inference in production-like setup
* Backend logic and file handling
* Practical application of deep learning

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 👤 Author

**Ganashree C N**

⭐ If you find this project useful, don’t forget to star the repository!
