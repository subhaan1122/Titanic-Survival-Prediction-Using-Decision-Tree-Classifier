🚢 Titanic Survival Prediction using Decision Tree:

This project builds a machine learning model to predict whether a passenger survived the Titanic disaster using a Decision Tree Classifier. We preprocess the dataset by selecting relevant features, handling missing values, encoding categorical data, and then training the model.

📌 Project Overview:

We:
- Load and explore the Titanic dataset
- Clean and preprocess the data
- Convert categorical variables into numeric
- Handle missing values
- Train a Decision Tree model
- Evaluate model accuracy

🧾 Features Used:

Feature	: Description
Pclass:	Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
Sex	Gender:  (encoded: male = 1, female = 2)
Age:	Age in years
Survived: 	Target (0 = No, 1 = Yes)

🧠 Model Used:

Decision Tree Classifier from scikit-learn: A simple, interpretable model that splits data based on feature values.

🧪 Model Evaluation:

- Training samples: 712
- Testing samples: 179
- Accuracy (on test set): ~77% (may vary slightly)

✅ Learnings:

- How to clean real-world data (drop columns, handle missing values)
- Categorical encoding (Sex)
- Training a simple decision tree model
- Measuring model accuracy

⭐ If you found this helpful, leave a star on the repo!
