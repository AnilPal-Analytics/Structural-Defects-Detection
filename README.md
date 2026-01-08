# Structural Defects Detection using AI

An **AI-assisted structural defect identification system** for the construction industry.  
This application analyzes uploaded structural images and generates a **detailed inspection report** using **Google Gemini AI**.

---

## 🚀 Features

- 📸 Upload images of structures (cracks, spalling, corrosion, etc.)
- 🧠 AI-powered defect detection using **Gemini 2.5 Flash Lite**
- 📄 Automatically generated inspection report
- 📊 Severity analysis (Low / Medium / High)
- 💰 Estimated repair cost (INR) and implementation time
- 🛠️ Short-term & long-term repair recommendations
- ⬇️ Downloadable report
- 🎯 Designed for civil & structural engineering use cases

---

## 🧠 Defects Identified

The system can detect and analyze:
- Cracks
- Spalling
- Corrosion
- Honeycombing
- Surface degradation
- Multiple defects in a single image

---

## 🛠️ Tech Stack

- **Python**
- **Streamlit** (Web Interface)
- **Google Generative AI (Gemini)**
- **Pillow (Image Processing)**
- **python-dotenv**
- **Virtual Environment (.venv)**

---

## 📂 Project Structure

```text
Structural-Defects-Detection/
│
├── webapp.py               # Main Streamlit application
├── requirements.txt        # Project dependencies
├── .env                    # API key (not committed)
├── README.md               # Project documentation
└── .venv/                  # Virtual environment
