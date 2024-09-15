# Heart Disease Classification

This project aims to predict whether a patient has heart disease using various machine learning algorithms. The dataset contains various health-related attributes and is used to train a model to make predictions.

## Project Structure

- **Project_1_Heart_Disease_Classification.ipynb**: The main Jupyter notebook for the heart disease classification project.
- **environment.yml**: Conda environment file to create a reproducible Python environment for this project.
- **heart-disease.csv**: The used dataset.

## Dataset

The dataset used for this project consists of various health indicators such as age, sex, chest pain type, resting blood pressure, cholesterol level, and others to determine whether a patient has heart disease.

### Features
- `age`: Age of the patient
- `sex`: Sex of the patient
- `cp`: Chest pain type
- `trestbps`: Resting blood pressure
- `chol`: Serum cholesterol level
- `fbs`: Fasting blood sugar
- `restecg`: Resting electrocardiographic results
- `thalach`: Maximum heart rate achieved
- `exang`: Exercise-induced angina
- `oldpeak`: ST depression induced by exercise relative to rest
- `slope`: Slope of the peak exercise ST segment
- `ca`: Number of major vessels colored by fluoroscopy
- `thal`: Thalassemia
- `target`: Diagnosis of heart disease (1 indicates presence of heart disease, 0 indicates absence)

## Installation

1. Clone the repository:
    ```bash
    git clone <repository-url>
    cd <repository-directory>
    ```

2. Set up the environment using Conda:
    ```bash
    conda env create -f environment.yml
    conda activate colab-env
    ```

3. Alternatively, install dependencies using pip:
    ```bash
    pip install -r requirements.txt
    ```

## Running the Project

Open the Jupyter notebook using the command below, and follow the steps in the notebook to run the project:
```bash
jupyter notebook Project_1_Heart_Disease_Classification.ipynb
