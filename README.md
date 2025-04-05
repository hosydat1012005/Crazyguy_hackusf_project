# Crazyguy_hackusf_project

# 🧠 AI-Powered Skin Cancer Classifier

This project aims to develop an AI model that classifies skin cancer lesions as benign or malignant using NIH imaging data and clinical data. Early detection of skin cancer is critical, and this model can help provide fast, non-invasive assessments to assist medical professionals and the public.

---

## 🚀 Project Goals

- 🖼️ Use NIH image datasets and clinical data
- ⚖️ Classify skin lesions as **benign** or **malignant**
- 🧪 Explore image classification + clinical features
- 🛠️ Deliver a simple prototype model with clear metrics

---

## 🧰 Tech Stack

- Python 3.8+
- Pandas, NumPy, scikit-learn
- OpenCV, Matplotlib
- TensorFlow or PyTorch (TBD)
- `med-minds` for querying NIH clinical data
- Docker + PostgreSQL for MINDS data access

---

## 📁 Directory Structure

skin-cancer-ai-classifier/
├── data/
│   ├── raw/                  # Raw downloaded datasets (images, clinical CSVs)
│   └── processed/            # Preprocessed data for model training
├── notebooks/
│   └── EDA.ipynb             # Exploratory Data Analysis
├── src/
│   ├── __init__.py
│   ├── data_loader.py        # Code to load/clean data
│   ├── model.py              # Model training and evaluation
│   └── utils.py              # Helper functions
├── main.py                   # Main runner script
├── requirements.txt          # Python dependencies
├── .env                      # Environment variables (PostgreSQL info)
├── README.md                 # Project overview
└── .gitignore


