# Stock-Prediction-Analysis-Altair


This project performs stock prediction analysis on the **Microsoft Stock dataset** from Kaggle using **Altair** for visualization and analysis. The goal is to predict future stock trends by analyzing historical data.


## Dataset

The dataset used in this project is the [Microsoft Stock Dataset](https://www.kaggle.com/datasets) from Kaggle. It contains historical data on Microsoft's stock prices, including:

- **Date**
- **Open**
- **High**
- **Low**
- **Close**
- **Volume**
- **Adjusted Close**

## Tools & Technologies

- **Altair**: For data visualization and interactive plots.
- **Pandas**: For data manipulation and preprocessing.
- **Scikit-learn**: For building prediction models (linear regression, decision trees, etc.).
- **Numpy**: For numerical computations.
- **Matplotlib/Seaborn**: For additional visualizations.
- **Jupyter Notebook**: For interactive code execution.

## Analysis Workflow

### Data Collection:

- Load the dataset from Kaggle and prepare it for analysis.

### Data Preprocessing:

- Handle missing values.
- Feature engineering (e.g., creating moving averages, returns).
- Data normalization for better model performance.

### Exploratory Data Analysis (EDA):

- Visualizing stock trends over time using Altair.
- Analyzing correlations between various features.

### Modeling:

- Implement stock price prediction models (Linear Regression, Decision Trees, etc.).
- Train-test split for model evaluation.

### Model Evaluation:

- Use metrics such as Mean Squared Error (MSE) and R-squared to assess performance.

### Prediction:

- Use the trained models to predict future stock prices.

### Visualization:

- Plot the predictions vs actual data using Altair.

## Results

- The model predicts future stock prices with reasonable accuracy.
- Interactive visualizations created using Altair allow for a detailed exploration of the data and predictions.

## Future Improvements

- Test additional machine learning algorithms (e.g., LSTM for time series).
- Improve feature engineering techniques.
- Include more stock indicators in the analysis.
