🩺 Diabetes Prediction using SVM – Streamlit App

This project is a Machine Learning web application built using Streamlit that predicts whether a person is diabetic or not based on health parameters.
The model used is a Support Vector Machine (SVM) trained on the PIMA Diabetes Dataset.

🚀 Features

✔️ Interactive Streamlit web interface

✔️ User-friendly sliders for all input features

✔️ Pre-trained SVM model (svm.sav)

✔️ Instant prediction result

✔️ Notebook (Sourav.ipynb) included for model training and analysis

📁 Project Structure
│── app.py                 # Streamlit application
│── svm.sav                # Trained SVM model
│── Sourav.ipynb           # Jupyter notebook (model training & EDA)
│── requirements.txt       # Dependencies
│── README.md              # Project documentation

🛠️ Technologies Used

Python

Streamlit

Scikit-learn

NumPy

Pandas

Pickle

📦 Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

2️⃣ Install dependencies
pip install -r requirements.txt

3️⃣ Run the Streamlit App
streamlit run app.py


Your app will open in the browser at:

http://localhost:8501

🧠 Model Details

Algorithm: Support Vector Machine (SVM)

Dataset: PIMA Indian Diabetes Dataset

Output:

0 → No Diabetes

1 → Diabetes Detected

🖥️ App Interface

The app collects the following user inputs:

Feature	Description
Pregnancies	Number of pregnancies
Glucose	Glucose concentration
Blood Pressure	Diastolic BP
Skin Thickness	Skin fold thickness
Insulin	Insulin level
BMI	Body Mass Index
Diabetes Pedigree Function	Genetic diabetes likelihood
Age	Age of the person

On clicking Predict, the app shows:

✅ Patient has No diabetes
or

⚠️ Patient has diabetes

📘 Jupyter Notebook Included

Sourav.ipynb contains:

Exploratory Data Analysis

Feature preprocessing

Model training

Evaluation metrics

Saving the trained SVM model

This helps you understand and reproduce the entire workflow.

🤝 Contributing

Feel free to fork this repository and submit pull requests for improvements.

📜 License

This project is open-source and free to use.
