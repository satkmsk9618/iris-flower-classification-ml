# Iris Flower Classification – Machine Learning Project

This project uses the classic **Iris dataset** to classify flower species (Setosa, Versicolor, Virginica) based on sepal and petal dimensions.  
It demonstrates a complete **machine learning workflow** 
—> from data loading and exploration to model training and evaluation 
—> implemented in Python using popular data science libraries.

---------

## Objective

To build and evaluate a **machine learning model** capable of predicting the species of Iris flowers using sepal and petal measurements.  
This project showcases the fundamental steps involved in developing an ML model for classification tasks.

---------

## Dataset Information

- **Dataset Name:** Iris Dataset  
- **Source:** https://www.kaggle.com/datasets/uciml/iris  
- **Number of Samples:** 150  
- **Features:**
  - Sepal Length (cm)  
  - Sepal Width (cm)  
  - Petal Length (cm)  
  - Petal Width (cm)  
- **Target:** Species (`setosa`, `versicolor`, `virginica`)

---------

## Project Workflow

The Jupyter notebook (`Iris_dataset.ipynb`) follows a clean, structured ML pipeline:

1. **Importing Libraries**
   - pandas, numpy, matplotlib, seaborn, scikit-learn

2. **Data Loading**
   - Load the Iris dataset from Scikit-learn or CSV file.

3. **Exploratory Data Analysis (EDA)**
   - Statistical summary  
   - Data visualization (pair plots, box plots, heatmaps)  
   - Correlation analysis  

4. **Data Preprocessing**
   - Handling missing values (if any)  
   - Feature encoding (if required)  
   - Train-test split  

5. **Model Training**
   - Trained with two models classifiers (Random Forest, SVM).  
   - Compared model accuracies.

6. **Model Evaluation**
   - Accuracy, Classification Report.

7. **Conclusion**
   - Identified the best-performing model and key observations from data analysis.

---------

## Model Results

| Model                | Accuracy |
|----------------------|-----------|
| Random Forest        | ~96-97% |
| SVM                  | ~93% |

> The **SVM Classifier** performed the best overall on this dataset.

---------

## Installation & Usage

### 1️Clone this repository
```bash
git clone https://github.com/satkmsk9618/iris-flower-classification-ml
cd iris-flower-classification-ml
```

### 2️⃣ Create a virtual environment (optional)
```bash
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
```

### 3️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Run the notebook
```bash
jupyter notebook Notebooks/Iris_dataset.ipynb
```

---------

## 📦 Requirements

```
numpy
pandas
matplotlib
seaborn
scikit-learn
jupyter
```

Save this as your `requirements.txt`.

---------

## Future Improvements

- Perform **hyperparameter tuning** for better accuracy.  
- Try **advanced models** like XGBoost or Gradient Boosting.  
- Deploy the model using **Streamlit** or **Flask**.  
- Convert the notebook into Python scripts for production-level structure.

---------

## Author

**Sathish Kupendra**  
M.Sc. Data Science, AI & Digital Business  
GISMA University of Applied Sciences, Germany  

📫 [LinkedIn](www.linkedin.com/in/sathish-kupendra-bb0aa3296)  
💻 [GitHub](https://github.com/satkmsk9618)

