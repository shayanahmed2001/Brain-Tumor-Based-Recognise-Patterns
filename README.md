# Brain-Tumor-Based-Recognise-Patterns
The aim of this project was to recognize patterns in brain tumor data by applying both classification and regression models. The project involved several key steps: data cleaning, data visualization, data transformation, data normalization, and the application of machine learning models.

Data Preprocessing
Data Cleaning:
Removed any missing or inconsistent data entries to ensure the dataset was complete and accurate.

Data Visualization:
Used various visualization techniques (e.g., histograms, scatter plots, box plots) to understand the distribution and relationships within the data.
Identified key features and patterns that could be useful for the modeling process.

Data Transformation:
Applied transformations to the data to enhance its suitability for machine learning models.
Included operations such as encoding categorical variables, normalizing numerical variables, and scaling the data.

Data Normalization:
Standardized the data to have a consistent scale, ensuring that all features contributed equally to the models.
Used techniques like MinMaxScaler to scale features to a range of 0 to 1.

Model Application
The project involved applying two models sequentially: a classification model followed by a regression model.

Classification Model:
Solved a classification problem present in the dataset.
Applied suitable classification algorithms DecisionTreeClassifier to classify the data into distinct categories.
Evaluated the model's performance using metrics such as accuracy, precision, recall, and F1-score.
Regression Model:
Recognized that the dataset contained a regression problem in addition to the classification problem so I used DecisionTreeRegressor for this.
Concatenated the results of the classification model as an additional independent variable for the regression model.
Applied a Decision Tree Regressor to predict the continuous target variable.
Evaluated the regression model's performance using metrics such as Mean Squared Error (MSE)..
