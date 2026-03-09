# ML1 Final Project

## About
This project is our code for the Final Project in the UChicago Machine Learning 1 Course for the Winter 2026 Quarter, where we predicted employee attrition with the dataset from Kaggle

## Authors
Cathy Nie, Monica Para, Hannah Ko, Kelly Sun, Victoria Li, Rhett Bergeson

## Running the Project

### Disclaimer
This project was developed using **Google Colab**. The notebooks include code to mount **Google Drive** to access files. If you run the notebooks locally, you may need to remove the Google Drive mounting code and update file paths.

---

## Setup

Clone the repository:

```bash
git clone https://github.com/mmpara27/ML1-Final-Project.git
cd ML1-Final-Project
```

## Run the Notebooks

1. Open the notebooks in **Google Colab**.

2. Mount Google Drive if prompted:

```python
from google.colab import drive
drive.mount('/content/drive')
```

### 3. Run the Notebooks

Run the notebooks **in the following order**:

1. `Data_Cleaning.ipynb`  
2. `Modeling.ipynb`  
3. `Modeling_Part2.ipynb`

The provided dataset is `employee_attrition_data.csv`

The first notebook cleans and prepares the dataset. The remaining notebooks train and evaluate the machine learning models.
