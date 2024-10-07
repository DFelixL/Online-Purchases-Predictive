This project is from my Final Data Analytics Project. This project focuses on analyzing revenue of online purchases to gain insights and create predictive model on revenue prediction.

Steps Involved:
1. Data Understanding:
    Firstly, the raw data is examined to identify key attributes, such as product related, visitor type, bouncerates, exitrates, etc. The structure, types of data, and potential relationships between attributes is also assessed to understand the scope of analysis.

2. Data Cleaning and Preprocessing:
    There are no missing records in the dataset. However, the month and visitor type will be encoded into numerical data. Irrelevant column is also removed with the help of insight from heatmap and business understanding.

3. Data Analysis & Visualization:
    Statistical methods and visualization tools is used to analyze patterns and trends over time. The visualization, such as box plot, histogram, and heatmap, is displayed to highlight key insights.

4. Model Selection, Training, and Evaluation: 
    There are total of 8 models displayed to gain the best Accuracy and F1-Score for further development, which are Cross Gradient, Light Gradient, Random Forest, and Gradient Boosting. Finally, Random Forest and Cross Gradient are used for stacking method with the help of SMOTE for over-sampling. These models are being trained and testes using the K-Fold method to remove bias. The evaluator used are averaged f1-score, accuracy, and confusion matrix

Insight gathered :
- The best model shows f1-score average of 96.89% which are combination of Random Forest and Cross Gradient
- K-Fold method shows that there are no significant bias, for the difference between each folds are between 0.01%
