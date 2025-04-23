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
   git clone https://github.com/aselya9185/streamlit-calculator.git

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt

## Run the App
You’ll need to run both the FastAPI server and the Streamlit frontend.

1. **Start the FastAPI backend**
   ```bash
   uvicorn fast_api:app --reload

2. **Start the Streamlit frontend**
   ```bash
   streamlit run main.py

## Files Overview
- calculator.py – Contains the calculate function that performs basic arithmetic operations based on the operation name and input numbers.
- fast_api.py – Sets up the FastAPI server. It defines the API endpoint and handles POST requests, calling the calculate function using data validated by Pydantic's BaseModel.
- main.py – The Streamlit frontend script. It allows users to choose operations and inputs interactively and communicates with the FastAPI backend to display the result.
- requirements.txt – Lists the Python packages needed to run the app (FastAPI, Uvicorn, Streamlit, etc.).
- README.md – Documentation and setup instructions for your project.

## Learning Outcome
This project helped me understand:
- How Streamlit works for rapid frontend development
- How FastAPI handles backend APIs
- How to make HTTP requests between them

