# Red-Wine-Data-Analysis
This project aims to predict the quality of red wine based on its physicochemical properties. The project utilizes a dataset containing various features such as fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, and alcohol.<br>

Methodology:<br>

1. Data Loading and Preprocessing:<br> The dataset is loaded and preprocessed by handling missing values, removing duplicates, and standardizing numerical features.<br>

2. Exploratory Data Analysis:<br> Exploratory data analysis is performed to gain insights into the data distribution, correlations, and potential outliers using visualizations such as histograms, pair plots, box plots, and heatmaps.<br>

3. Feature Engineering: One-hot encoding is applied to categorical features. Numerical features were scaled using StandardScaler.<br>

4. Model Training:<br> The data is split into training and testing sets. A Linear Regression model is trained on the training data to predict wine quality.<br>

5. Model Evaluation:<br> The model's performance is evaluated using metrics such as Mean Squared Error (MSE) and R-squared score on the testing data.<br>

6. Model Deployment:<br> The trained model is saved as a pickle file for future use.<br>

Feel free to download the code and data.
