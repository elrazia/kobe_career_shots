## Anatomy of a Made Shot
##### Predicting Kobe Bryant's Career Makes

<br/>
***Objective:*** Using a [dataset](https://www.kaggle.com/c/kobe-bryant-shot-selection) of every shot Kobe Bryant took in his career, try and predict which shots were makes and which were misses.
<br/>
<br/>
***Tools:*** Python (Pandas, Numpy, Sklearn, Matplotlib)
<br/>
<br/>
***Methodology:*** Obtained Kaggle dataset (also available via NBA API). Cleaned data and use RFE to select important features. Fit Logistic Regression and Random Forest models to data. Tuned hyperparameters using GridSearch.
<br/>
<br/>
***Conclusions:*** Kobe Bryant was a remarkably consistent player over the course of his 19-year career. An ordinary basketball player would likely have difficulty making baskets from distance, making baskets with time winding down, making baskets vs. certain teams. Kobe didn't show any of these weaknesses. On the contrary, his consistency spanned decades of aging, roster transitions, injury seasons, and coaching changes. Feature selection highlighted shot type and shot area as the two key predictors of Kobe Bryant's makes. Looking at left vs. right vs. center court and hook-shot vs. fadeaway vs. floater could tell you more about whether or not a shot was going in than who was guarding the "Black Mamba" or what kind of a season he was having. Additional feature engineering would improve the predictive power of the models.
