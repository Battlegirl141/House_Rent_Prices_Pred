# 🏡 House Rent Price Prediction
## 🌟 Project Overview
This project is an end-to-end machine learning regression model designed to accurately predict the rental price of residential properties. It demonstrates a comprehensive understanding of the data science workflow, from initial data cleaning and feature engineering to building, training, and evaluating a robust Deep Learning (Neural Network) model.

The primary goal was to minimize the prediction error (Residuals) and deliver a reliable tool for estimating market-rate rent prices based on various property attributes.

### 🛠 Key Features & Methodology
This project showcases the following core data science and machine learning skills:

Data Preprocessing & Cleaning:

Handling of missing values using appropriate imputation strategies.

Feature Engineering and transformation of categorical data (e.g., location, apartment type) into a machine-readable format.

Implementation of Feature Scaling (StandardScaler) to normalize numerical features, ensuring the Neural Network converges efficiently.

### Model Development:

Employed a Keras/TensorFlow Neural Network to capture complex, non-linear relationships within the dataset, leading to more accurate predictions than traditional linear models.

Used sklearn for efficient data splitting into training and test sets.

### Performance Evaluation:

Model performance was rigorously evaluated using metrics suitable for regression tasks (e.g., Mean Squared Error, R-squared).

Analysis of Actual vs. Predicted scatter plots confirmed a strong positive correlation, indicating high predictive accuracy, particularly for mid-range market values.

### 📈 Performance Summary
The final model exhibited strong predictive power for the majority of the data.

Metric	Performance	Insight
Prediction Accuracy	High correlation between Actual and Predicted prices.	The model successfully learned the underlying market dynamics.
Identified Challenge	Higher residual errors observed for high-value properties (outliers).	Highlights a clear path for future model iteration and robustness improvements.

### 💻 Tech Stack
The project was developed using a standard Python data science environment:

Category	Tools / Libraries

Language	Python (3.10)

Data Analysis	pandas, numpy

Machine Learning	scikit-learn (for preprocessing and splitting)

Deep Learning	TensorFlow / Keras (for the core prediction model)

Visualization	matplotlib

Serialization	joblib (for saving trained scalers)
