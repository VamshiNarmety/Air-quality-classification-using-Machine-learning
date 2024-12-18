# Air Quality Classification Using Machine Learning

This project focuses on predicting air quality based on pollutant concentrations using machine learning. Instead of calculating the AQI through a formula, we directly predict the AQI category based on the concentration of various pollutants.

# setup the project
## How to Run
1. Install Python 3.10.x
1. Clone this repository:
   ```bash
   git clone https://github.com/VamshiNarmety/Air-quality-classification-using-Machine-learning-DAI-101-.git
   cd Air-quality-classification-using-Machine-learning-DAI-101-
2. `pip3 install -r requirements.txt`
3. jupyter notebook
4. Run the notebooks in order:
   - First, proceed to the EDA notebook (part-1_EDA).
   - Then, execute the modeling notebook (part-2_modelling).

## Steps to Run the Project

### 1. Exploratory Data Analysis (EDA)

- Run `Air quality classification using machine learning(part-1_EDA).ipynb` for Exploratory Data Analysis (EDA).
- This step includes:
  - Visualizing time-series data for vehicular and industrial pollution across cities.
  - Analyzing pollution levels before and after COVID-19.
  - Comparing AQI trends in metropolitan and non-metropolitan cities.

### 2. Machine Learning Modeling

- Run `Air quality classification using machine learning(part-2_modelling).ipynb` for the ML modeling.
- In this step:
  - I evaluate various machine learning models.
  - After testing several algorithms, the **Random Forest Classifier** is selected for its high accuracy and generalization capability, showing 100% accuracy in predicting the AQI categories.

# Dataset

The dataset used in this project is from Kaggle and contains air quality data from multiple cities across India between 2015 and 2020. It includes various pollutants' concentrations such as particulate matter (PM2.5, PM10), nitrogen dioxide (NO2), sulfur dioxide (SO2), and ozone (O3), among others.

- You can access the dataset here: [Air Quality Data in India (2015-2020)](https://www.kaggle.com/datasets/rohanrao/air-quality-data-in-india)

# Key Findings in EDA

- **Pollution Analysis**:
  - Time-series analysis for vehicular and industrial pollution across cities, comparing trends before and after the COVID-19 lockdown.
  - Cities like **Delhi** and **Gurugram** showed the highest pollution levels, while **Shillong** had the least pollution.
  
- **AQI Trends**:
  - The analysis also explored AQI trends in both **metropolitan** and **non-metropolitan** cities, revealing insights about urban and rural air quality.

# Model Selection and Performance

- **Model**: After evaluating various models, I selected the **Random Forest Classifier** for its ability to generalize well and reduce overfitting, compared to SVM and Decision Tree models.
- **Performance**: The Random Forest Classifier achieved **100% accuracy** in predicting AQI categories, making it the final model for this project.

# Rendering Issues

Sometimes, Jupyter notebooks might not render properly on GitHub. If you face such issues, you can download the notebook or view it using [nbviewer](https://nbviewer.jupyter.org/).
