# Manufacturing Output Prediction

A machine learning project that predicts manufacturing equipment output using **Linear Regression**, with **FastAPI** backend and **Streamlit** frontend for real-time predictions.

## Project Structure

- `Backend/` → FastAPI backend code  
- `Frontend/` → Streamlit frontend code  
- `Model/` → Trained model and pickle files  
- `Data/` → Dataset used for training  
- `tns_project_1.ipynb` → Colab notebook with preprocessing and model building  
- `README.md` → This file  
- `README.txt` → Instructions in plain text  
- `LICENSE`  
- `.gitignore`  

## Instructions to Run the Project

1. Extract the zip file to any folder.  
2. Install required packages:

```bash
pip install -r requirements.txt

Or manually install:

```bash
pip install streamlit fastapi uvicorn pandas scikit-learn

cd Backend
python -m uvicorn backend:app --reload

cd Backend
python -m uvicorn backend:app --reload

cd ../Frontend
streamlit run app.py

Open Streamlit in the browser and use the app.
  
The tns_project_1.ipynb notebook contains data preprocessing, model training, and evaluation.
The trained model is saved in the Model/ folder and loaded by the backend for predictions.
