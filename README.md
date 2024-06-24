# Car-Price-Prediction-ML-Model
This project aims to predict used car prices using machine learning techniques. It involves comprehensive data exploration, feature engineering, model selection, training, and evaluation to develop an accurate predictive model.

**Dataset**
The dataset comprises information on various used cars, including attributes such as car name, year of manufacture, selling price, kilometers driven, fuel type, seller type, transmission type, and ownership details.

**Sample Data**
| name                       | year | selling_price | km_driven | fuel  | seller_type | transmission | owner       |
|--------------------------  |------|---------------|-----------|-------|-------------|--------------|-------------|
| Maruti 800 AC              | 2007 | 60000         | 70000     | Petrol| Individual  | Manual       | First Owner |
| Hyundai Verna 1.6 SX       | 2012 | 600000        | 100000    | Diesel| Individual  | Manual       | First Owner |
| Datsun RediGO T Option     | 2017 | 250000        | 46000     | Petrol| Individual  | Manual       | First Owner |
| Honda Amaze VX i-DTEC      | 2014 | 450000        | 141000    | Diesel| Individual  | Manual       | Second Owner|
| Hyundai Xcent 1.2 Kappa S  | 2016 | 550000        | 25000     | Petrol| Individual  | Manual       | First Owner |

**Project Goals and Steps**
**1. Data Exploration**
 - Conducted thorough analysis to understand data distributions, identify outliers, and visualize key trends using histograms and scatter plots.

**2. Feature Engineering**
 - Engineered new features like car_age derived from the year of manufacture to capture the vehicle's age.
 - Transformed categorical variables using one-hot encoding to prepare them for machine learning models.
   
**3. Model Selection and Training**
 - Selected regression models including Linear Regression, Random Forest, and Gradient Boosting based on their suitability for the dataset.
 - Developed pipelines for preprocessing and model training to streamline the workflow.
   
**4. Model Evaluation**
 - Evaluated model performance using metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).
 - Utilized cross-validation techniques to ensure robustness and reliability of the models.
 
**5. Hyperparameter Tuning**
 - Employed Grid Search and Random Search to optimize hyperparameters of selected models, enhancing prediction accuracy.
   
**Results and Conclusion**
 - Achieved a prediction accuracy of 60.18% after rigorous model tuning and evaluation.
   
This project not only provided insights into predicting car prices but also enhanced proficiency in data preprocessing, model selection, and performance evaluation set.
