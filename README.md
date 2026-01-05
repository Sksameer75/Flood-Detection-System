# Flood-Detection-System
# Real-Time Floodwater Mapping using Satellite Image Segmentation (U-Net)

## 📌 Project Overview
This project is a Deep Learning application designed to detect and map floodwater from satellite imagery in real-time. It utilizes a **U-Net++ architecture** with an **EfficientNet-B4 encoder** to perform semantic segmentation, accurately identifying water bodies and calculating the percentage of flooded areas.

The system features a **Flask** backend for model inference and a **React (Vite)** frontend for an interactive user interface.

## 🚀 Key Features
* **AI-Powered Detection:** Uses PyTorch and Segmentation Models PyTorch (SMP) for high-accuracy flood masking.
* **Real-Time Visualization:** Generates an overlay mask showing the exact location of floodwaters.
* **Damage Assessment:** Automatically calculates the percentage of the area affected by flooding.
* **Interactive UI:** Modern, responsive interface built with React and Tailwind CSS.

## 🛠️ Tech Stack
* **Frontend:** React.js, Vite, Tailwind CSS
* **Backend:** Python, Flask, Flask-CORS
* **Deep Learning:** PyTorch, U-Net++, EfficientNet, Albumentations, OpenCV

## 📂 Project Structure
* `/backend`: Contains the Flask API, model inference logic (`app.py`), and the trained model.
* `/frontend`: Contains the React web application.
* `/dataset`: (Optional) Scripts for synthetic data generation and training.

## 🔧 How to Run
1.  **Backend:**
    ```bash
    cd backend
    pip install -r requirements.txt
    python app.py
    ```
2.  **Frontend:**
    ```bash
    cd frontend
    npm install
    npm run dev
    ```
