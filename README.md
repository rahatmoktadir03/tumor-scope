🧠 TumorScope – Brain Tumor Classification with Deep Learning & Gemini AI

📌 Project Overview
TumorScope is a Streamlit-based web app that classifies brain MRI scans into four categories:
Glioma
Meningioma
Pituitary Tumor
No Tumor

It uses:
✅ Xception (Transfer Learning)
✅ Custom CNN model
✅ Saliency Maps for Explainability
✅ Gemini 1.5 Flash for Medical Explanation

✅ Features
✔ Upload Brain MRI images for instant classification
✔ Two Models to Choose From: Transfer Learning & Custom CNN
✔ Saliency Maps to visualize important brain regions
✔ AI-Powered Explanation using Gemini 1.5 Flash
✔ Interactive Probability Charts
✔ Deployed on Streamlit Cloud

🚀 Tech Stack
| Component          | Technology         |
| ------------------ | ------------------ |
| **Frontend**       | Streamlit          |
| **Model Training** | TensorFlow / Keras |
| **Explainability** | Gemini 1.5 Flash   |
| **Visualization**  | Plotly, OpenCV     |
| **Deployment**     | Streamlit Cloud    |

🔧 Setup Instructions
1. Clone the Repository
git clone https://github.com/your-username/tumor-scope.git
cd tumor-scope
2. Install Dependencies 
pip install -r requirements.txt
3. Add Your API Key
Create a .env file in the root:
GOOGLE_API_KEY=your-gemini-api-key
4. Run Locally
streamlit run streamlit_app.py

📊 Challenges Completed
✅ Achieved 98% accuracy with Custom CNN
✅ Added Transfer Learning with Xception (99% accuracy)
✅ Integrated Gemini for Medical Explanation
✅ Added Saliency Map Visualization

🎯 Future Enhancements
✅ Allow user to chat with MRI scan
✅ Add multi-model comparison dashboard
✅ Generate detailed diagnostic reports
