<p align="center">
    <img src="https://upload.wikimedia.org/wikipedia/commons/0/08/Netflix_2015_logo.svg" width="300"/>
</p>

# Netflix Global Top 10 Performance

Can we predict how many hours a Netflix title will be viewed based on its first two weeks in the Global Top 10? What trends influence what we watch? This project explores these questions using both classical statistical methods and modern machine learning techniques. <br>

### 🔍 Project Overview
- 📈 **R Viewership Analysis**: explored Global Top 10 viewership, comparing Netflix shows to historic global TV audiences
- 📊 **Multiple Linear Regression**: built a baseline statistical model to assess variable significance
- 🤖 **Machine Learning**: tested and tuned ensemble models to improve predictive performance

### 💡Key results:
 - Humanity has spent more time watching **Squid Game: Season 1** than the Moon landings 🌕
 - Live TV still affects streaming demand: Viewership for **Stranger Things 4** dropped during the FIFA World Cup qualifiers ⚽
 - **88.3%** of variation in total hours viewed explained by 🌲 **Random Forest model**  <br>
 - 📺 **TV shows** tend to perform better than 🍿 **Films** <br>
 - **Week 2 viewership** is strongest predictor of Netflix title's success <br>

### ⚙️ Methods & Techniques
#### R Viewership Analysis
 - Visualised trends using ggplot2
 - Estimated global viewership per show
 - 📖 Jupyter Notebook: [GitHub](https://github.com/dpb24/netflix-global-top-10-performance/blob/main/r-viewership-analysis/netflix-most-popular-shows.ipynb) | [Kaggle](https://www.kaggle.com/code/davidpbriggs/netflix-most-popular-shows)  <br>
 
#### Multiple Linear Regression
 - Data Preprocessing: log transformation, IQR-based outlier removal
 - Model Diagnostics: checked assumptions (homoscedasticity, multicollinearity, Q-Q plots)
 - ANOVA & Tukey's Test: tested category differences in viewership
 - 📖 Jupyter Notebook: [GitHub](https://github.com/dpb24/netflix-global-top-10-performance/blob/main/python-linear-regression/netflix-global-top-10-performance-predictor-lr.ipynb) | [Kaggle](https://www.kaggle.com/code/davidpbriggs/netflix-global-top-10-performance-predictor-lr)  <br>
 
#### Machine Learning Models
 - Models Evaluated: Decision Tree, Random Forest, Gradient Boosting, XGBoost
 - Hyperparameter Tuning: GridSearchCV
 - Metrics Used: R², Adjusted R², Mean Squared Error (MSE)
 - 📖 Jupyter notebook: [GitHub](https://github.com/dpb24/netflix-global-top-10-performance/blob/main/python-ml-model/netflix-global-top-10-performance-predictor-ml.ipynb) | [Kaggle](https://www.kaggle.com/code/davidpbriggs/netflix-global-top-10-performance-predictor-ml)  <br> <br>

<p align="center">
    <img src="r-viewership-analysis/visuals/netflix_historic_comparisons.png" width="800"/>
    <img src="python-ml-model/visuals/netflix_global_top_10_weekly.png" width="800"/>
    <img src="python-ml-model/visuals/ml_model_performance1.png" width="800"/>
    <img src="python-ml-model/visuals/ml_model_performance2.png" width="800"/>
</p>
