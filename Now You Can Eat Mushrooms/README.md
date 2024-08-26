# Now You Can Eat Mushrooms

I got GOLD MEDAL for this project
## Project Overview

This project aims to build a machine learning model that predicts whether a mushroom is edible or poisonous based on its physical characteristics. The dataset used contains 22 features and over 3 million entries, representing various mushroom species with labels indicating whether each mushroom is safe to eat or not.

## Dataset

The dataset is sourced from a popular mushroom classification dataset and includes features such as cap shape, cap color, gill size, odor, and habitat. The target variable is a binary class representing whether the mushroom is edible or poisonous.

## Objective

The main objective of this project is to develop a highly accurate predictive model to classify mushrooms as edible or poisonous. This involves the following steps:
- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Feature selection and engineering
- Model training and evaluation

## Methodology

1. **Data Preprocessing**: Handling missing values, encoding categorical variables, and splitting the dataset into training and testing sets.
2. **Exploratory Data Analysis**: Visualizing and understanding the distribution and relationships between features.
3. **Feature Engineering**: Applying rare encoding to categorical features and selecting relevant features based on their importance.
4. **Model Training**: Multiple models were trained, including XGBoost, LGBM, and CatBoost. 
5. **Hyperparameter Tuning**: Using Optuna for tuning the model hyperparameters.
6. **Evaluation**: Models were evaluated using accuracy and Matthew’s Correlation Coefficient (MCC) to select the best performing model.

## Results

The final model achieved an impressive accuracy of **99.22%** on the test set. The use of ensemble learning with XGBoost, LGBM, and CatBoost further boosted the model's performance, yielding a robust classifier capable of distinguishing between edible and poisonous mushrooms.

## Conclusion

This project demonstrates the power of machine learning in solving real-world classification problems. The high accuracy achieved suggests that the model can be reliably used for mushroom classification, potentially reducing the risk of mushroom poisoning.

## How to Use

1. Clone this repository.
2. Install the necessary dependencies.
3. Run the notebook to preprocess the data, train the models, and evaluate the results.
4. Use the trained model to classify new mushroom data.

## Future Work

- Explore other ensemble techniques to improve performance further.
- Investigate the use of deep learning models for this classification task.
- Extend the project to include additional mushroom species and more diverse datasets.

## Acknowledgments

Special thanks to the dataset creators and the Kaggle community for providing valuable insights and suggestions that helped shape this project.
