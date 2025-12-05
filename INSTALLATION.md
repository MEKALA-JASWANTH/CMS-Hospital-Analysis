# Installation & Setup Guide

## Quick Start

### 1. Clone Repository

git clone https://github.com/MEKALA-JASWANTH/CMS-Hospital-Analysis.git
cd CMS-Hospital-Analysis

### 2. Create Virtual Environment

Windows:
python -m venv venv
venv\Scripts\activate

Mac/Linux:
python3 -m venv venv
source venv/bin/activate

### 3. Install Dependencies

pip install -r requirements.txt

### 4. Add Dataset

Place HospInfo.csv in the data/ folder

### 5. Run App

streamlit run app.py

App opens at http://localhost:8501

---

## Features
- Interactive Web Dashboard
- Hospital Data Analysis
- ML Quality Predictions (91.23% accuracy)
- Statistical Visualizations
- Filter by State, Ownership, Type

---

## Troubleshooting

ModuleNotFoundError:
pip install --upgrade -r requirements.txt

Port 8501 already in use:
streamlit run app.py --server.port 8502

---

## System Requirements
- Python 3.8+
- 4GB RAM
- 500MB disk space

Happy Analyzing! 🏥
