# Streamlit + FastAPI Calculator

This is a simple calculator project built using **Streamlit** for the frontend and **FastAPI** for the backend. It was created by following a [tutorial on Medium](https://medium.com/codex/streamlit-fastapi-%EF%B8%8F-the-ingredients-you-need-for-your-next-data-science-recipe-ffbeb5f76a92) as a way to learn how to integrate Streamlit with FastAPI.

## What It Does
- A user-friendly UI created with Streamlit
- A backend API with FastAPI to compute math expressions
- Communicates between frontend and backend using HTTP requests

---

## Installation

1. **Clone the repo:**
   ```bash
   git clone [https://github.com/yourusername/streamlit-fastapi-calculator.git](https://github.com/aselya9185/streamlit-calculator.git)

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt

## Run the App
You’ll need to run both the FastAPI server and the Streamlit frontend.

**1. Start the FastAPI backend**
bash
Копировать
Редактировать
uvicorn fast_api:app --reload
This runs the API at http://127.0.0.1:8000.

2. Start the Streamlit frontend
In a new terminal window/tab (same directory):

bash
Копировать
Редактировать
streamlit run main.py
The frontend will open in your browser (default: http://localhost:8501).

🛠 Files Overview
main.py – Streamlit UI logic

fast_api.py – FastAPI server logic

requirements.txt – Python dependencies

README.md – This file ✨

📚 Learning Outcome
This project helped me understand:

How Streamlit works for rapid frontend development

How FastAPI handles backend APIs

How to make HTTP requests between them

