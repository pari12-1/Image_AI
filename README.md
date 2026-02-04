# 🖼️ Image_AI

An AI-powered image processing backend built with **FastAPI** and **Open router**.  
This project allows users to upload images and process them using modern machine learning models via a fast API service.

---

## 🚀 Features

- Upload images via API endpoints  
- Using Ai API from open router  
- Fast and scalable FastAPI backend  
- Simple and clean project structure
- Deployed using render

---

## 🛠️ Tech Stack

- FastAPI  
- HuggingFace Hub  
- Pillow (image processing)  
- Requests  
- Python Multipart (file uploads)  

---

## 📦 Requirements
---
huggingface_hub

pillow

python-multipart

fastapi

requests

uvicorn

---

## 📁 Project Structure (example)
---

Image_AI/

│
├── backend/

│ └── app.py

├── requirements.txt

├── README.md

└── .env

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone git@github.com:pari12-1/Image_AI.git
cd Image_AI
```
## create virtual environment

```
python -m venv .venv
```
## Activate it in windows

```
.venv\Scripts\activate
```

## Install dependencies
```
pip install -r requirements.txt
```

# Run your project
```
uvicorn backend.app:app --reload
```

