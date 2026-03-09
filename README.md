# ML1 Final Project

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

1. `data_cleaning.ipynb`  
2. `modeling_notebook_1.ipynb`  
3. `modeling_notebook_2.ipynb`  

The first notebook cleans and prepares the dataset. The remaining notebooks train and evaluate the machine learning models.
