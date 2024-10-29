# Flower Species Prediction Using Machine Learning 
This project leverages machine learning to classify flower species based on specific characteristics, such as petal length and width. Trained on the Iris Dataset, the model can accurately predict whether a flower is of the Setosa, Versicolor, or Virginica species.
 The project is deployed with **Streamlit** to offer an interactive experience for users.

## Included Files 
- **requirements.txt**: Contains the libraries needed to run the project.
- **trained_model.sav**: The trained model file.
- **iris.ipynb**: Jupyter Notebook with code for training and analysis.
- **streamlit_app.py**: The Streamlit app code for running the application.
- **IRIS.csv**: Dataset used to train the model.

 ## How to Run
 1. Install the required libraries:
```bash
 pip install -r requirements.txt
```

2. Run the interactive application with:
 ```
    streamlit run streamlit_app.py
```

## Project Details 
* **Data**: The model uses the Iris Dataset, which includes flower dimension details. 
* **Model**: A trained prediction model saved in trained_model.sav. 
* **App**: The Streamlit app provides an easy-to-use interface where users can input flower characteristics to predict its type.

**Developed and deployed with Streamlit**

## Demo App

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://iris-prediction0.streamlit.app/)

