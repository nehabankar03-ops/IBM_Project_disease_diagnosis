# Diagnosis Prediction Project

## Project Description
This project uses machine learning to predict a **diagnosis** class from patient-related clinical features. A preprocessing pipeline handles missing values, numerical scaling, and categorical encoding before training a Random Forest classifier.

## Problem Statement
**To predict diagnosis** using available patient/clinical features.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Random Forest Classifier

## Dataset
Dataset file expected by the notebook: `diagnosis_dataset.csv`

**Dataset link:** Add the original public dataset URL here before submission.

## Project Files
- `NehaBankar_DiagnosisPrediction.ipynb` - complete project code
- `requirements.txt` - required Python libraries
- `NehaBankarDiagnosisPrediction_ProjectReport.docx` - project documentation
- `README.md` - project overview and setup instructions

## Setup / Run Instructions
1. Install Python 3.
2. Open Command Prompt/Terminal in the project folder.
3. Install dependencies:
   `pip install -r requirements.txt`
4. Put the dataset in the same folder as the notebook.
5. Make sure the dataset filename is `diagnosis_dataset.csv`.
6. Make sure the target column is named `Diagnosis`. If not, change `TARGET` in the notebook.
7. Open Jupyter Notebook:
   `jupyter notebook`
8. Open the `.ipynb` file and run the cells from top to bottom.

## Key Information
The model is evaluated using accuracy, classification report and confusion matrix. Results depend on the dataset.

## Contact
**Neha Bankar**  
Email/Phone: nehabankar03@gmail.com 

> Educational project only. The prediction should not be used as a medical diagnosis or treatment recommendation.
