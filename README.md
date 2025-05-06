# Predicting Stock Market Prices and Trends
Predicting Stock Market Direction and Magnitude with Machine Learning Algorithms and Neural Networks

## Team

**Daniel Santoyo**  
Built the XGBoost classification and regression models. Performed multiple rounds of tuning, and achieved the best model performance overall.

**Pine Nguyen**

Focused on the LSTM classification model. Handled data preprocessing, structured time-series sequences, and tuned hyperparameters using Hyperband. Evaluated performance with validation accuracy, confusion matrices, and recall to improve directional prediction.


**Thanh Tran**  
Developed the LSTM regression model. Trained the model on close price sequences and proposed a hybrid trend classification method using regression output ranges.

**Kenny Amanor**  
Implemented and tuned the Transformer model for stock price magnitude regression. Adapted the model from a Kaggle reference, handled sequence generation, performed tuning with Keras Tuner, and interpreted the model's generalization and volatility prediction challenges.

---

## How to Run the Code
1. **Clone the Repository** 
   ```bash
   git clone https://github.com/Dani-santoyo/Stock-Market-Predictor.git
   cd Stock-Market-Predictor
   
2. **Set Up Your Environment**
   - This project was developed using Anaconda and run in Jupyter Notebook, both of which were used throughout ITEC 4700
     All the required libraries (pandas, numpy, matplotlib, scikit-learn, tensorflow) were part of what we used in class, so no additional unfamiliar packages are needed.
   - To set up the environment:
   - Open Anaconda Navigator
   -  Create a new environment (or use base)
   -  Launch Jupyter Notebook from Anaconda
   -  Navigate to the folder containing the notebooks and run any of them
    #### Options B: Using the Command Line
    ````bash
      conda create -n stock-ai-env python=3.10
      conda activate stock-ai-env
      conda install jupyter pandas numpy matplotlib scikit-learn tensorflow xgboost
      jupyter notebook
    
3. **Run Any Notebook**
  Open the notebook of your choice using Jupyter or VS Code:

    - Transformer.ipynb

   -  XGBoost.ipynb

    - LSTM_Classification.ipynb

    - Price_Regression_Prediction_LSTM.ipynb
  
 4. **Dataset Location**
  Ensure that the stock data file (BATS_AAPL, 60 clean.csv) is placed in the same folder as the notebook.
  Update the file paths in the notebooks if needed.
