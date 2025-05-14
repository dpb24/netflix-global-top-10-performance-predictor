# Netflix Global Top 10 Performance Predictor (Python)

### 🎬 Predicting Netflix Title Performance with machine learning 📊 <br>


Can we predict how many hours a Netflix title will be viewed based on its first two weeks in the Global Top 10? What trends influence what we watch? This project explores these questions using machine learning techniques. <br>

### 📊 Statistical Approach:
 -  **Data Preprocessing:** removed outliers beyond the IQR for model robustness <br>
 -  **Machine Learning:** tested Decision Tree, Random Forest, Gradient Boosting, and XGBoost models <br>
 -  **Hyperparameter Tuning:** used GridSearchCV to optimise model parameters  <br>
 -  **Model Evaluation:** evaluated model performance using R², adjusted R², and Mean Squared Error (MSE) <br>
 -  **Python packages:** used Pandas, Matplotlib, Scikit-learn (sklearn) <br>


### 💡Key results:
 - **88.3%** of variation in total hours viewed explained by 🌲 Random Forest model  <br>
 - **Week 2 viewership** is strongest predictor of Netflix title's success <br>
 - **Category matters:** 📺 TV shows tend to perform better than 🍿 Films  <br> <br>


📊 Explore the Jupyter notebook: [GitHub](https://github.com/dpb24/netflix-global-top-10-performance-predictor-ml/blob/main/netflix-global-top-10-performance-predictor-ml.ipynb) | [Kaggle](https://www.kaggle.com/code/davidpbriggs/netflix-global-top-10-performance-predictor-ml)  <br>


<div style="display: flex; justify-content: center; align-items: center;">
    <img src="netflix_global_top_10_weekly.png" width="800">
    <img src="ml_model_performance1.png" width="800">
    <img src="ml_model_performance2.png" width="800">
</div>
