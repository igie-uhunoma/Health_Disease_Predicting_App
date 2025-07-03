
# 🩺 Heart Failure Risk Predictor · IGIE MODEL

![GitHub repo size](https://img.shields.io/github/repo-size/your-github-handle/heart-failure-ai?color=6f42c1)
![License](https://img.shields.io/github/license/your-github-handle/heart-failure-ai?color=f58529)
![Built with love](https://img.shields.io/badge/built%20with-%E2%9D%A4-ff69b4?style=flat)

> **Predict heart-failure risk in seconds, right from your browser.**  
> An AI-powered clinical decision-support tool built by **Igie Uhunoma**—aspiring lawyer, human-rights advocate, adventure lover, and budding ML engineer.

---

## ✨ Project Highlights
- **Accurate ML model** trained on real clinical data (299+ patient records)  
- **Responsive web interface** with an Instagram-inspired gradient and hospital-grade form styling  
- One-click **real-time predictions** served via a lightweight Flask API  
- Fully container-ready & deployable to Render, Heroku, or any Docker host  
- Easy to extend: swap in larger datasets or plug directly into EMR systems

---

## 🛠️ Tech Stack
| Layer             | Tech                                                         |
|-------------------|--------------------------------------------------------------|
| ✨ Front-end UI   | HTML 5 · CSS 3 (custom + Gradient palette) · Google Fonts     |
| ⚙️ Back-end API  | **Flask 2** · `joblib` model loader                           |
| 🧠 ML Model       | Scikit-learn (Logistic Regression / Random Forest baseline)  |
| 📈 EDA & Training | Pandas · NumPy · Matplotlib · Seaborn                        |
| 🚀 Deployment     | Render / Heroku / Docker                                     |

---

## 🚀 Quick Start (Local)

```bash
# 1▸ Clone repo
git clone https://github.com/your-github-handle/heart-failure-ai.git
cd heart-failure-ai

# 2▸ Create virtual environment
python -m venv venv
source venv/Scripts/activate   # Linux/WSL: source venv/bin/activate

# 3▸ Install dependencies
pip install -r requirements.txt

# 4▸ Run the app 🎉
python app.py
# visit http://127.0.0.1:5000 in your browser
```

---

## 🖼️ Screenshots  
| Home Form | Prediction Result |
|-----------|-------------------|
| _Add a screenshot here_ | _Add another screenshot here_ |

---

## 📚 Project Structure
```
heart-failure-ai/
├── app.py                 # Flask server
├── model.pkl              # Trained ML model
├── requirements.txt
├── templates/
│   ├── index.html         # Gradient medical form
│   └── result.html        # Result display
└── static/                # (Optional) CSS / JS / images
```

---

## 👩🏽‍💻 Author
**Igie Uhunoma** – aspiring lawyer, human-rights champion, and machine-learning enthusiast.  
Connect on [Instagram](https://instagram.com/your-handle) · [LinkedIn](https://linkedin.com/in/your-profile)

---

## ⚖️ License
Distributed under the MIT License. See `LICENSE` for details.
