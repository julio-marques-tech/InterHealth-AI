# 🧠 InterHealth AI - Data Integration Layer

This is the first layer of the **InterHealth AI** platform — an interoperable health data system designed to modernize patient data management and integration across diverse healthcare environments in the United States 🇺🇸.

---

## 🚦 Lab Status

✅ PostgreSQL database configured  
✅ Flask backend running locally  
✅ REST API for patients (POST & GET) implemented  
✅ Integration with GitHub completed  

---

## 🎯 Learning Objectives

- Build a REST API using Flask
- Connect and operate with PostgreSQL
- Handle JSON data in healthcare context
- Create a scalable backend structure for future business rules and AI models

---

## 🧰 Technologies & Tools

- 🐍 Python 3.11
- 🔥 Flask
- 🐘 PostgreSQL
- 🐳 Docker (future layers)
- ☁️ Oracle Cloud (next layer deployment)
- 📦 GitHub for versioning

---

## 🚀 How to Run Locally

```bash
# Clone the repo
git clone https://github.com/julio-marques-tech/InterHealth-AI.git
cd InterHealth-AI

# Create virtual environment
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Set FLASK_APP and run
export FLASK_APP=backend.app
flask run
🧪 Example Tests
➕ Add patient:
bash
Copiar
Editar
curl -X POST http://127.0.0.1:5000/patients \
-H "Content-Type: application/json" \
-d '{"name": "Alice", "age": 30, "gender": "Female", "diagnosis": "Hypertension"}'
📥 Get all patients:
bash
Copiar
Editar
curl -X GET http://127.0.0.1:5000/patients

## 📁 Project Structure
graphql
Copiar
Editar
InterHealth-AI/
├── backend/               # Flask app and routes
├── data/                  # Future ETL scripts or datasets
├── docs/                  # Documentation and diagrams
├── frontend/              # (To be implemented)
├── requirements.txt       # Python dependencies
└── README.md
---
⚖️ License and Intellectual Use
This project is licensed under the
Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.

© 2025 Julio Marques. All rights reserved for commercial applications.

You are free to:

Share and adapt the code for non-commercial use

Attribute the original author (Julio Marques)

Use it for educational and research purposes

Commercial usage, redistribution or incorporation into proprietary solutions is not permitted without explicit permission.

🧑‍⚕️ Built by Julio Marques — promoting secure, intelligent, and interoperable healthcare solutions for the U.S. and beyond.
