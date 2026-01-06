# 🧠 K-Nearest Neighbors (KNN) Machine Learning Web App

A Machine Learning web application that predicts **purchase behavior** (Yes/No) based on user input features using the **K-Nearest Neighbors (KNN)** algorithm.
The model is built with **Scikit-Learn**, served via **Flask**, and deployed on **Vercel**.

🔗 **Live Demo:**
👉 [https://purchase-predictor-ai.vercel.app/](https://purchase-predictor-ai.vercel.app/)

🔗 **Repository:**
👉 [https://github.com/karthikeyantoff/KNN_Algorithm](https://github.com/karthikeyantoff/KNN_Algorithm)

---

## 📌 About the Project

This project uses **K-Nearest Neighbors (KNN)**, a simple and powerful supervised machine learning algorithm for classification.
The goal is to predict **whether a user is likely to make a purchase** based on features such as age, income, and usage patterns.

The web app provides an interactive UI where users can enter values, and the backend Flask API processes them and returns real-time predictions using the trained model.

---

## 🛠️ Tech Stack

* **Frontend:** HTML
* **Backend:** Python, Flask
* **Machine Learning:** Scikit-Learn, Joblib
* **Model Used:** K-Nearest Neighbors (KNN)
* **Deployment:** Vercel

---

## ▶️ How to Run Locally

Follow these steps to run the project on your computer:

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/karthikeyantoff/KNN_Algorithm.git
cd KNN_Algorithm
```

### 2️⃣ Install Dependencies

Make sure Python is installed, then run:

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Flask App

```bash
python app.py
```

### 4️⃣ Open in Browser

Go to:

```
http://127.0.0.1:5000/
```

---

## 🤖 Model Details

* **Algorithm:** K-Nearest Neighbors (KNN)
* **Library Used:** Scikit-Learn
* **Learning Type:** Supervised Learning (Classification)
* **Model Saving Tool:** Joblib (`.pkl` file)

---

## 🔢 Input Features (Example)

The model predicts purchase likelihood based on features such as:

* Age
* Estimated Salary
* Gender (encoded)
* Previous Purchase History
* Usage Frequency
  *(Exact inputs depend on the dataset used in training.)*

---

## 📤 Output

* **Prediction:**

  * `0` → Not Likely to Purchase
  * `1` → Likely to Purchase

The result is displayed directly on the web interface after form submission.

---

## 📂 Project Structure

```
KNN_Algorithm/
│
├── templates/             # HTML frontend
│   └── index.html
├── static/                # CSS / assets
├── app.py                 # Flask backend
├── train.py               # Model training script
├── model.pkl              # Trained KNN model
├── requirements.txt       # Project dependencies
├── vercel.json            # Vercel deployment config
└── README.md
```

---

## 🌐 Frontend & Backend Flow

1. User enters feature values in UI form
2. Form sends data to Flask backend
3. Backend loads trained KNN model
4. Model predicts class label
5. Result is shown in UI

---

## 🤝 Contributing

Contributions are always welcome!
You can:

* Improve UI/UX
* Add evaluation metrics (accuracy, confusion matrix)
* Tune KNN hyperparameters (k values, distance metrics)
* Optimize performance

Just fork the repo, make improvements, then create a pull request 

---

## 👨‍💻 Author

**Karthikeyan T**
Machine Learning | AI Engineer | Web-AI Projects Enthusiast 
