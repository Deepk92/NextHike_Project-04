# NextHike_Project-04
Feature Extraction and Price Prediction for Mobile Phones using Python

Project Description:
In this project, I worked with a dataset that contains detailed information about various mobile phones, including their model, color, memory, RAM, battery capacity, rear camera specifications, front camera specifications, presence of AI lens, mobile height, processor, and most importantly, the price. My primary goal is to develop a predictive model for mobile phone prices.

Steps and Methods involved in the Project :
1) Data Exploration :- Started by loading and exploring the dataset to understand its structure, data types, the range of values for each feature etc.
2) Data Preprocessing :- Handled missing values, outliers and inconsistencies in the dataset. Converted categorical variables into a suitable numerical format, using One-hot encoding, Ordinal encoding and Label Encoding.
3) Feature Extraction :- Performed feature extraction to identify the most relevant features that strongly affect the price of mobile phones with Principal Component Analysis (PCA).
4) Model Building and Evaluation :- Splitted the dataset into training and testing sets and Developed a machine learning model for price prediction using various algorithms such as Linear Regression, Decision tree, Random forest and Gradient Boosting and evaluated the performance matrics such as mean absolute error, root mean squared error, R2 score.
5) Feature Importance Analysis :-  Analyzed the feature importances obtained from the model to confirm the significance of the features identified during the feature extraction phase.
6) Dashboard Creation Using Tableau :- Created a Dynamic Dashboard including multiple sheets with a minimum of 6-7 important data visualization charts to showcase the project requirement.
7) Report, Visualization and Recommendations :- Created a comprehensive report or presentation that summarizes the project's findings. Include visualizations and insights about feature importance and their impact on price prediction.

Python Libraries Used - Data science libraries such as Numpy, Pandas, Matplotlib, Seaborn and Machine learning libraries such as Scikit-learn (for Python) for building and evaluating the predictive model in the Jupyter Notebook Environment.



Project Conclusion :-
The model's reliance on PC1 more than PC2 aligns with the nature of PCA, where the first few components are designed to capture the most variance. Both the components are used (with significant weights) indicates that the feature extraction phase was successful in identifying meaningful patterns in the data. The dominance of PC1 suggests that most information relevant for predicting the mobile phone prices is encapsulated in this single component. However, with an average importance of approximately 0.21 (21 %), PC2 also plays a significant role in predictions.

Memory Size (RAM and Storage) : High positive loading in PC1. It means that Phone with more Memory and Storage tends to be priced higher and are important for performance-focused consumers.






