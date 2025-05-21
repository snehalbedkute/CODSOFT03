#  CodSoft Internship - Task 3: Iris Flower Classification

##  Aim
The aim of this task is to build a machine learning model that can accurately classify the species of Iris flowers based on their physical attributes such as sepal length, sepal width, petal length, and petal width. This is a supervised classification problem using the well-known Iris dataset.

---

##  Dataset
The dataset contains **150 samples** with **4 numerical features** and **1 target label**:

- Features: `sepal_length`, `sepal_width`, `petal_length`, `petal_width`
- Target: `species` (Iris-setosa, Iris-versicolor, Iris-virginica)

Data source: `IRIS.csv`

---

##  Libraries Used
The following Python libraries were used to complete this task:
- `pandas`
- `matplotlib.pyplot` & `seaborn`
- `sklearn.preprocessing`  
- `sklearn.model_selection` 
- `sklearn.ensemble`  
- `sklearn.metrics` 

---

##  Summary of the Task

1. **Data Loading & Exploration**  
    Loaded the dataset using pandas and examined basic statistics and structure.  
    Verified the dataset has no missing values.
2. **Data Visualization**  
    Used Seaborn and Matplotlib for plotting pair plots, boxplots, and heatmaps.  
    Visualized feature distributions and correlations.
3. **Preprocessing**  
    Applied label encoding to the target variable.  
    Scaled features using StandardScaler.
4. **Model Building**  
    Split the dataset into training and testing sets (80/20 split).  
    Trained a Random Forest Classifier.
5. **Model Evaluation**  
    Evaluated using accuracy score, classification report, and confusion matrix.  
    Achieved high classification accuracy.

---

##  Conclusion

This project successfully demonstrates how machine learning can be used to classify Iris flower species using a Random Forest model. The model showed high accuracy, validating the effectiveness of feature engineering and supervised learning methods on structured datasets.


