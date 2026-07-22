**Diabetic Patient Prediction using Machine Learning**

📌 **Project Overview**

Diabetic Prediction is a Machine Learning project developed to predict whether a person is likely to have diabetes based on specific health-related parameters.

The project uses Machine Learning techniques to analyze patient data and generate diabetes predictions. The trained model is integrated into a simple Streamlit application for making predictions.

## 🎯 Objectives

- To analyze diabetes-related patient data.
- To preprocess and prepare the dataset for Machine Learning.
- To train a Machine Learning model for diabetes prediction.
- To evaluate the performance of the trained model.
- To predict whether a patient is diabetic or not based on input parameters.
- To develop a simple and user-friendly prediction application.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Jupyter Notebook
- Pickle

## 📊 Dataset

The project uses a diabetes dataset containing health-related parameters of patients.
The input parameters include:

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age
The model uses these parameters to predict the diabetes status of a patient.

## ⚙️ Project Workflow

1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis
4. Feature Selection
5. Data Scaling
6. Model Training
7. Model Evaluation
8. Saving the Trained Model
9. Diabetes Prediction using Streamlit Application

## 🚀 How to Run the Project

### Step 1: Clone the Repository

```bash
git clone <your-github-repository-link>
```

### Step 2: Open the Project Folder

```bash
cd "Diabetic Patient Prediction"
```

### Step 3: Install Required Libraries

```bash
pip install -r requirements.txt
```

### Step 4: Run the Streamlit Application

```bash
streamlit run app.py
```

## 💻 Application

The application allows users to enter patient health parameters and predicts whether the patient is likely to be:

- Diabetic
- Not Diabetic

## 📈 Model

The Machine Learning model is trained using the available diabetes dataset. The trained model and scaler are saved and used by the application to generate predictions for new patient data.

## 📁 Files Description

| File | Description |
|------|-------------|
| `app.py` | Streamlit application for diabetes prediction |
| `data.csv` | Dataset used for the project |
| `implementation.ipynb` | Jupyter Notebook containing project implementation |
| `model.pkl` | Trained Machine Learning model |
| `scaler.pkl` | Saved data scaler |
| `requirements.txt` | Required Python libraries |
| `README.md` | Project documentation |

## 🔮 Future Scope

- Improve model accuracy using advanced Machine Learning algorithms.
- Add more patient health parameters.
- Deploy the application online.
- Add visualization and data analysis features.
- Implement multiple Machine Learning models and compare their performance.

## 👩‍💻 Author

**Pradnya Patil**

## 📜 License

This project is created for educational and learning purposes.

