# 🧠 TumorScope – Brain Tumor Classification with Deep Learning & Gemini AI

![Streamlit](https://img.shields.io/badge/Streamlit-Cloud-success?logo=streamlit)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow)
![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Status](https://img.shields.io/badge/Status-Deployed-success)

---

## 📖 Overview

**TumorScope** is a web application that classifies **brain MRI scans** into four categories:
- **Glioma**
- **Meningioma**
- **Pituitary Tumor**
- **No Tumor**

The app uses:
- **Xception (Transfer Learning)**
- **Custom CNN Model**
- **Saliency Maps** for interpretability
- **Gemini 1.5 Flash (Google AI)** to generate concise **medical explanations** for predictions

The project is deployed on **Streamlit Cloud** and provides an interactive user experience for radiologists, researchers, and students.

---

## ✨ Key Features

- **Upload Brain MRI Images** for classification
- **Dual-Model Selection**: Transfer Learning (Xception) or Custom CNN
- **Saliency Map Generation** to visualize important image regions
- **AI-Powered Explanations** via Gemini 1.5 Flash
- **Interactive Probability Charts** with Plotly
- **Secure Deployment** on Streamlit Cloud

---

## 🛠 Tech Stack

| Component         | Technology              |
|-------------------|-------------------------|
| **Frontend**      | Streamlit               |
| **Model Training**| TensorFlow / Keras      |
| **Explainability**| Gemini 1.5 Flash        |
| **Visualization** | OpenCV, Plotly          |
| **Deployment**    | Streamlit Cloud         |


---

## 🚀 Getting Started

### 1️⃣ Clone the Repo
```bash
git clone https://github.com/rahatmoktadir03/tumor-scope.git
cd tumor-scope
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Add Gemini API Key
 - Create a .env file in the project root:
   ```init
   GOOGLE_API_KEY=your-gemini-api-key
   ```

### 4️⃣ Run Locally
```bash
streamlit run streamlit_app.py
```

---

## 📊 Models and Accuracy
- Xception (Transfer Learning) – ~99% accuracy
- Custom CNN – ~98% accuracy
- Saliency Maps highlight critical regions for model interpretability

---

## 🔮 Future Improvements
- Chat with MRI scan (using multimodal LLMs)
- Compare multiple models side-by-side
- Generate detailed diagnostic reports for doctors
