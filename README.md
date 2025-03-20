# Lung Cancer Prediction Using Machine Learning

This project leverages various machine learning models to predict lung cancer based on patient data. It involves data preprocessing, model training, and performance evaluation using key metrics like accuracy, precision, recall, and F1-score.

## Dataset
The dataset contains 309 rows and 16 columns with the following features:
- **GENDER** (M/F)
- **AGE**
- **SMOKING**
- **YELLOW_FINGERS**
- **ANXIETY**
- **PEER_PRESSURE**
- **CHRONIC DISEASE**
- **FATIGUE**
- **ALLERGY**
- **WHEEZING**
- **ALCOHOL CONSUMING**
- **COUGHING**
- **SHORTNESS OF BREATH**
- **SWALLOWING DIFFICULTY**
- **CHEST PAIN**
- **LUNG_CANCER** (Target Variable)

## Data Preprocessing
1. **Data Cleaning:**
   - Missing values checked (no missing values found).
   - Data types converted to integers for compatibility with machine learning models.
2. **Encoding Categorical Variables:**
   - `GENDER` mapped to {M: 1, F: 2}.
   - `LUNG_CANCER` mapped to {YES: 1, NO: 2}.
3. **Data Splitting:**
   - 2/3 for training, 1/3 for testing using `train_test_split()`.

## Machine Learning Models
### 1. Logistic Regression
- **Accuracy:** 0.883
- **Precision:** 0.895
- **Recall:** 0.977
- **F1 Score:** 0.934

### 2. K-Nearest Neighbors (KNN)
- **Accuracy:** 0.874
- **Precision:** 0.878
- **Recall:** 0.989
- **F1 Score:** 0.930

### 3. Decision Tree
- **Accuracy:** 0.874
- **Precision:** 0.878
- **Recall:** 0.989
- **F1 Score:** 0.930

### 4. Support Vector Machine (SVM)
- **Accuracy:** 0.845
- **Precision:** 0.845
- **Recall:** 1.0
- **F1 Score:** 0.916

### 5. Naive Bayes
- **Accuracy:** 0.864
- **Precision:** 0.910
- **Recall:** 0.931
- **F1 Score:** 0.920

### 6. Random Forest
- **Accuracy:** 0.893
- **Precision:** 0.904
- **Recall:** 0.977
- **F1 Score:** 0.939

## Model Evaluation Metrics
- **Confusion Matrix:** Visualized using Seaborn heatmaps.
- **Precision, Recall, and F1-score:** Calculated to assess model performance in detail.

## Data Visualization
- **Correlation Heatmap:** Visualizes feature relationships.
- **Distribution Plots:** Histograms for each feature to understand data distribution.

## Libraries Used
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## How to Run
1. Install dependencies:
```bash
pip install pandas matplotlib seaborn scikit-learn
```
2. Load the dataset: Ensure `survey_lung_cancer.csv` is in the working directory.
3. Run the Python script to execute the entire pipeline.

## Conclusion
This project effectively demonstrates lung cancer prediction using various machine learning models, with Random Forest achieving the highest performance.

For any questions or contributions, feel free to reach out!
- [Email](mailto:abhayr24564@gmail.com) - Mail for any colabs or queries!
- [LinkedIn](https://www.linkedin.com/in/abhay-singh312/) - Let's connect!
- [Github](https://github.com/Abhay-Singh312) - Check out my other works!
