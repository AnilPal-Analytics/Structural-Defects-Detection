# Structural Defects Detection using AI

An **AI-assisted structural defect identification system** for the construction industry.  
This Streamlit-based web application uses **Google Gemini Vision (Generative AI)** to analyze uploaded images of structures and automatically generate a **professional defect assessment report**.

---

## 🚀 Features

- 📸 Upload images of structural elements (JPEG, PNG, WEBP)
- 🧠 AI-powered defect detection using **Google Gemini 2.5**
- 🏢 Identifies common structural defects such as:
  - Cracks
  - Spalling
  - Corrosion
  - Honeycombing
  - Other visible construction defects
- 📊 Severity assessment (Low / Medium / High)
- ⏳ Estimated time before permanent damage
- 💰 Short-term & long-term repair solutions with **estimated cost (INR)**
- 🛡️ Preventive measures to avoid future defects
- 📄 Auto-generated **downloadable inspection report**
- ⚡ Simple & interactive **Streamlit UI**

---

## 🧠 How It Works (AI Flow)

1. User uploads an image of a structure
2. Image + prompt are sent to **Google Gemini Vision Model**
3. AI analyzes defects visually
4. A structured engineering-style report is generated
5. User can download the report

---

## 🛠️ Tech Stack

- **Python**
- **Streamlit** – Web UI
- **Google Generative AI (Gemini Vision)**
- **Pillow (PIL)** – Image handling
- **python-dotenv** – Secure API key management

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


