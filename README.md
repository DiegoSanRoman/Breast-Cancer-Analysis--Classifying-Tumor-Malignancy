# Breast Cancer Analysis: Classifying Tumor Malignancy


## Project Overview
This project leverages state-of-the-art machine learning techniques to accurately classify breast cancer tumors as malignant or benign based on key cellular nucleus features. Using the comprehensive [Breast Cancer Dataset](docs/Breast_Cancer_Dataset.csv), the project implements a full workflow that includes robust data preprocessing, feature engineering, and model selection.

Key aspects of the project include:

- **Data Preprocessing:**  
  • Handling outliers using strategies such as removal or replacement (with mean/median values).  
  • Normalization of numerical features to ensure consistency and improve model performance.  
  • Dimensionality reduction through Principal Component Analysis (PCA) for effective feature selection.

- **Model Development:**  
  Multiple supervised learning models are implemented and evaluated, including:  
  • K-Nearest Neighbors (KNN)  
  • Decision Trees  
  • Random Forests  
  • Logistic Regression  
  … among others.

- **Evaluation & Validation:**  
  Cross-validation techniques, grid search for hyperparameter tuning, and visual performance analyses (e.g., accuracy curves, confusion matrices) are used to select the best performing models.


## Requirements
- Pyhton
- Jupyter Notebook
- Libraries: matplotlib, nbformat, numpy, pandas, scikit-learn, seaborn

You can install them by:
```sh
pip install -r requirements.txt
```


## Usage
To run the analysis:
1. Clone this repository.
2. Install the required packages using the provided `requirements.txt` file.
3. Open and run the [BreastCancerMain.ipynb](BreastCancerMain.ipynb) notebook in Jupyter Notebook.


## Authors
This project was developed by:
| [<img src="https://avatars.githubusercontent.com/u/128000512?v=4" width=115><br><sub>Fabian Bayona<br>fcbayona</sub>](https://github.com/fabiancbc) | [<img src="https://avatars.githubusercontent.com/u/113380669?v=4" width=115><br><sub>Diego San Romn Posada<br>dsanromn</sub>](https://github.com/Diego100495878) | [<img src="https://avatars.githubusercontent.com/u/158266903?v=4" width=115><br><sub>Daniel Gomez Martin-Ambrosio<br>dgomezma</sub>](https://github.com/100495687) |  [<img src="https://avatars.githubusercontent.com/u/158503957?v=4&size=64" width=115><br><sub>Jorge Hernáez Ayuso<br>jhernaez</sub>](https://github.com/100495761)
| :---: | :---: | :---: | :---: |