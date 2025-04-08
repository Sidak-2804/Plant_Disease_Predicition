# 🌿 Plant Disease Predictor

Welcome to the **Plant Disease Predictor** — a beautifully crafted web application that helps identify plant leaf diseases from uploaded images. The goal of this project is to aid farmers, researchers, and plant lovers in diagnosing plant diseases early using the power of machine learning and an interactive frontend interface.

---

## 🎯 Project Objective

Early identification of plant diseases is crucial to ensure healthy crop yields. This project aims to simulate a frontend interface that enables users to upload images of plant leaves and view disease predictions, with a backend-ready design that can be connected to an ML model trained on the PlantVillage dataset.

---

## 🌟 Features

- 🌱 Upload plant leaf image through a user-friendly interface
- 👀 Instant preview of uploaded image
- 🔍 Simulated plant disease prediction with a loading animation
- 🎨 Cream and green UI with sticky navbar for smooth navigation
- 🍃 CSS-based animated falling leaves effect
- 📱 Responsive design for desktop and mobile
- 💡 Backend-ready layout to plug in real ML model

---

## 🧠 Dataset Used

We used the publicly available PlantVillage dataset for training the backend ML model (not included in this frontend-only version).

🔗 **[New Plant Diseases Dataset on Kaggle]([https://www.kaggle.com/datasets/emmarex/plantdisease](https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset))**

- Contains more than a lakh images across 38 disease categories
- Includes both healthy and diseased samples
- Covers common crops like apple, corn, grape, potato, tomato, and more

---

## 🧰 Tech Stack

| Layer       | Technology         |
|-------------|--------------------|
| Frontend    | HTML5, CSS3, JavaScript |
| Styling     | Custom CSS, gradients, animations |
| ML Model    | TensorFlow / Keras     |
| Format      | `.keras` trained model |
---

## 🛠️ How It Works

1. User uploads an image of a plant leaf.
2. The image is previewed immediately using JavaScript.
3. When the user clicks “Predict Disease”, the app simulates a loading spinner.
4. After a delay, a dummy result like **“Powdery Mildew”** is displayed.
5. This system is designed to be backend-ready — just plug in a Python Flask API and a model.

---

## 📸 Sample Results

## 📸 Sample Results

### ✅ Prediction Output
![Prediction Output](./screenshots/Screenshot_2025-04-02_215443.png)

### 🟩 Disease Prediction
![Disease Prediction](./screenshots/Screenshot_2025-04-02_215454.png)

### 🖼️ Frontend UI
![Frontend UI](./screenshots/Screenshot_2025-04-09_000747.png)
