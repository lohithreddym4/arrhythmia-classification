python -m venv venv
venv\Scripts\activate
pip install streamlit joblib pandas tensorflow scikit-learn
streamlit run app.py
deactivate
pip freeze > requirements.txt
pip install -r requirements.txt
