# 🍃 CorpCare - Potato Leaf Disease Detection - Mini Project

## 📌 Overview
This project is a **Potato Leaf Disease Detection** system that utilizes **Deep Learning** and **Computer Vision** to classify diseases affecting potato leaves. The goal is to help farmers detect diseases early, improving crop yield and reducing losses.

The model is trained using **Convolutional Neural Networks (CNNs)** on a dataset containing images of healthy and diseased potato leaves.

## 🎥 Demo Video  
https://user-images.githubusercontent.com/SamK1828/DEMONSTRATION.mp4

🎬 Watch the live demo below or **[Click Here](demo_video/DEMONSTRATION.mp4)** to download and view the video.  

<video width="700" controls>
  <source src="screenshots/demo.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

---

## 🚀 Features
- Classifies potato leaf images into **Healthy** or **Diseased** categories.
- Uses a **CNN-based model** trained on real leaf images.
- A **web-based frontend** for easy image upload and classification.
- **Fast and accurate predictions** with a user-friendly interface.
- Built with **React.js, Flask, TensorFlow/Keras, and OpenCV**.

---

## 🛠️ Tech Stack
### **Frontend (User Interface)**
- React.js
- Material UI
- Axios (for API calls)

### **Backend (Model Processing)**
- Flask (Python-based API)
- TensorFlow/Keras (Deep Learning)
- OpenCV (Image Processing)
- NumPy & Pandas (Data Handling)

---

## 📂 Project Structure
```
Potato-Leaf-Disease-Detection/
│-- backend/               # Flask API & Model
│   ├── model/             # Trained CNN Model
│   ├── app.py             # Flask API
│   ├── requirements.txt   # Backend dependencies
│   ├── train_model.py     # Script for training model (optional)
│
│-- frontend/              # React.js Web UI
│   ├── src/               # React components and logic
│   ├── public/            # Static assets
│   ├── package.json       # Frontend dependencies
│
│-- dataset/               # Images for training/testing
│-- README.md              # Project documentation
```

---

## ⚡ Installation & Setup

### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/yourusername/Potato-Leaf-Disease-Detection.git
cd Potato-Leaf-Disease-Detection
```

### **2️⃣ Setup Backend**
```sh
cd backend
python -m venv venv  # Create a virtual environment
source venv/bin/activate  # Activate (Mac/Linux)
venv\Scripts\activate  # Activate (Windows)

pip install -r requirements.txt  # Install dependencies
python app.py  # Run the Flask API
```

### **3️⃣ Setup Frontend**
```sh
cd frontend
npm install  # Install dependencies
npm start  # Start React app
```

The frontend should now be running at **http://localhost:3000**, and the backend at **http://localhost:5000**.

---

## 🎯 How to Use
1. Open the web application.
2. Upload an image of a potato leaf.
3. Click on the **"Detect Disease"** button.
4. The model predicts if the leaf is **Healthy** or **Diseased**.
5. If diseased, suggestions for treatment are provided.

---

## 🧪 Model Training (Optional)
If you want to **train the model from scratch**, run:
```sh
cd backend
python train_model.py
```
This requires a labeled dataset of potato leaves.

---

## 📚 Dataset
The dataset used consists of images categorized into:
- **Healthy Leaves**
- **Diseased Leaves (Late Blight, Early Blight, etc.)**

Dataset Source: [Kaggle PlantVillage Dataset](https://www.kaggle.com/datasets)

---

## 🛠️ Troubleshooting
### **Backend Issues**
- If Flask doesn’t start, check for missing dependencies:
  ```sh
  pip install -r requirements.txt
  ```
- If the model is missing, ensure `model.h5` exists in `backend/model/`.

### **Frontend Issues**
- If `npm start` fails, try:
  ```sh
  rm -rf node_modules package-lock.json
  npm install
  npm start
  ```

---

## 📌 Future Improvements
- Improve model accuracy with more data.
- Add more disease categories.
- Deploy the project using **Docker** or **Cloud Services**.

---

## 🙌 Contributors
- **[Your Name]** - Developer
- **[Your Teammates]** - Support & Testing

---

## 📜 License
This project is licensed under the **MIT License**. You are free to use, modify, and distribute it.

---

## ⭐ Acknowledgments
- **TensorFlow & Keras** for deep learning.
- **Flask & React.js** for web development.
- **PlantVillage Dataset** for providing training images.

---

🚀 **Enjoy coding!** If you found this useful, give it a ⭐ on GitHub!
```
