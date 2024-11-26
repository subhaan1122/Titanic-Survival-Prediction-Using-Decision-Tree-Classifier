This project predicts the survival of passengers on the Titanic based on their attributes such as gender, age, and class using a Decision Tree Classifier. It demonstrates basic data preprocessing, feature engineering, and classification techniques.

-> Features: 

1. Data Preprocessing:
- Cleans the dataset by handling missing values and encoding categorical variables.
- Drops unnecessary columns like Name, Cabin, and Ticket.
  
2. Decision Tree Classifier:
- Trains a machine learning model to classify passengers as survived or not survived.
  
3. Model Evaluation:
- Evaluates the classifier's performance using the accuracy score

-> Technologies Used:
- Python: Programming language.
- Pandas: Data preprocessing and manipulation.
- Scikit-learn: Machine learning library.

-> How It Works:

1. Data Loading:
- Reads the Titanic dataset in CSV format.
- Data Preprocessing:

2. Drops irrelevant columns.
- Encodes categorical data (e.g., mapping gender to numeric values).
- Fills missing values in the Age column with the mean age.
  
3. Model Training:
-Fits a Decision Tree Classifier on the processed data.

4. Prediction and Evaluation:
- Predicts survival outcomes and evaluates the model's accuracy.
