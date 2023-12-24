# In-Vehicle-Coupon-Recommendations

## Dataset
The dataset used in this project contains information about various aspects of driving scenarios, including the destination, time of day, weather conditions, passengers in the car, and more. It provides the necessary features to analyze and predict coupon acceptance.
## Author

- [@chrisinyama](https://github.com/chrisinyama/In-Vehicle-Coupon-Recommendation-Analysis)


## Tools
Jupyter Notebook

## Libraries used 

NumPy

Pandas

Seaborn

Matplotlib

scikit-learn

imblearn
## Project Structure
**Import Libraries**: 

This section includes the necessary libraries imported for data processing, visualization, and modeling. The libraries used in this project include NumPy, Pandas, Seaborn, Matplotlib, scikit-learn, and more.

**Loading the Dataset**: 

This section focuses on loading the dataset into the project. It provides code snippets to read the dataset using Pandas and displays a sample of the data.

**Data Preprocessing**: 

This section includes data preprocessing steps such as handling missing values, feature scaling, and encoding categorical variables. It demonstrates the use of techniques like SimpleImputer, StandardScaler, and OneHotEncoder.

**Comprehensive Data Analysis**: 

Conducted in-depth exploratory data analysis, visualizations, and statistical insights to gain a deep understanding of the dataset.
This section explores the dataset to gain insights and understand the relationships between variables. It includes data visualization using Seaborn and Matplotlib to identify patterns and correlations.

**Advanced Machine Learning Techniques**: 

This section covers the modeling part of the project. It includes splitting the dataset into training and testing sets, building classification models such as  Decision Tree, and Random Forest. It evaluates the models using various metrics such as accuracy, confusion matrix, and classification report. The section also includes hyperparameter tuning using GridSearchCV to optimize model performance.

**Feature Selection**: 

This section focuses on feature selection techniques to identify the most important features for the prediction task. It demonstrates the use of SelectFromModel to select relevant features.

**Handling Class Imbalance**: 

This section addresses the issue of class imbalance in the dataset using the Synthetic Minority Over-sampling Technique (SMOTE). It shows how to oversample the minority class to improve model performance.
## Usage/Examples

```python
import pandas as pd

in_vehicle_coupon = pd.read_csv("in-vehicle-coupon-recommendation.csv")

in_vehicle_coupon

```


## Results/Findings

**Model Comparison**

Random Forest demonstrated higher overall accuracy, while Gradient Boosting was more effective in correctly identifying positive instances (coupon acceptance).

**Performance Metrics**

The study focused on accuracy as the main metric but also evaluated precision, recall, and F1-score to ensure a comprehensive assessment, given the dataset's potential imbalance.

**Conclusions and Future Directions**

The comparative analysis concluded that RandomForest, while more accurate overall, might be complemented by GradientBoosting in specific scenarios. The study's insights guide future work, including further model tuning, exploration of additional features, and potentially adopting other ensemble methods to enhance predictive performance.
## Recommendations
**Based on the  analysis, We recommend the following actions**:

Model Selection:

For a balance of overall accuracy and effective identification of positive instances (coupon acceptance), consider using the Random Forest model. It demonstrated higher accuracy in general predictions.
However, for scenarios where correctly identifying positive instances is critical, Gradient Boosting might be preferable, as it showed strength in this aspect.

Future Work:

Explore additional features that could further enhance the predictive capabilities of the models. Continuous improvement is essential in adapting to evolving consumer behavior.
Investigate the adoption of other ensemble methods or advanced techniques to boost predictive performance and robustness.
## Limitations

Algorithm Sensitivity:

The selected machine learning algorithms, Random Forest and Gradient Boosting, have their strengths and weaknesses. The models are sensitive to hyperparameter choices, and achieving the right balance requires careful tuning. 
## Installation
**To reproduce the analysis, follow these steps**:

Ensure that the necessary libraries are installed.

Download the Jupyter Notebook and the CSV file.

Run the Jupyter Notebook and execute the code cells to perform the analysis.

    
## Acknowledgements

 The stock-keeping data used in this project is sourced from [https://archive.ics.uci.edu/dataset/603/in+vehicle+coupon+recommendation].

