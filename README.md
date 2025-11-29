# 🩺 Medicine Recommendation System

An AI-powered system that predicts diseases and recommends suitable medicines, descriptions, precautions, workouts, and diets based on user symptoms. Built using **Python**, **Flask**, and **scikit-learn (v1.4.2)**, this project helps users make informed health decisions using machine learning models.

---

## 🚀 Features
- Predicts disease based on entered symptoms  
- Recommends medicines, precautions, workouts, and diets  
- Supports multiple ML models (SVC, RandomForest, GradientBoosting, KNN, MultinomialNB)  
- Uses pre-trained `.pkl` models for fast predictions  
- Simple and interactive interface  

---

## ⚙️ Tech Stack
- **Language:** Python  
- **Framework:** Flask  
- **Libraries:** scikit-learn==1.4.2, pandas, numpy, pickle  
- **Environment:** Jupyter Notebook / VS Code  

---

## 🧠 Models Used
| Model | File |
|--------|------|
| Support Vector Classifier | models/svc.pkl |
| Random Forest | models/random_forest.pkl |
| Gradient Boosting | models/gradient_boosting.pkl |
| K-Nearest Neighbors | models/knn.pkl |
| Multinomial Naive Bayes | models/multinomial_nb.pkl |

---

## 🧩 Setup Instructions

# Clone the repository
git clone https://github.com/yourusername/Medicine-Recommendation-System.git
cd Medicine-Recommendation-System

# Create a virtual environment
python -m venv venv
venv\Scripts\activate        # (Windows)
# source venv/bin/activate   # (macOS/Linux)

# Install dependencies
pip install -r requirements.txt
# or manually
pip install scikit-learn==1.4.2 numpy pandas flask


📁 Project Structure

Medicine-Recommendation-System/
│
├── models/
│   ├── svc.pkl
│   ├── random_forest.pkl
│   ├── gradient_boosting.pkl
│   ├── knn.pkl
│   └── multinomial_nb.pkl
│
├── app.py
├── helper.py
├── train_models.ipynb
├── requirements.txt
└── README.md

👨‍💻 Author

Nishant Kumar
📧 Email: nishantkr2003nna@gmail.com

🎓 Student | Developer | AI Enthusiast


🪪 License

This project is open-source and available under the MIT License © 2025 Nishant Kumar

---

✅ **How to use:**  
1. Copy everything above.  
2. Create a file named `README.md` in your project folder (`Medicine-Recommendation-System/`).  
3. Paste the content.  
4. Save it.  

It’s now **GitHub-ready** — with perfect markdown formatting, headings, tables, and code blocks for easy readability.
