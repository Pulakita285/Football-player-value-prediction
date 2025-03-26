# Football player value prediction

Authors: Pulakita Maity, Raman Pathak, Saatwika Singh Sisodia  

## Project Overview 
The football transfer market is highly competitive, requiring accurate player valuations for strategic team and financial planning. Traditional valuation methods rely on subjective judgments and simple statistical models, which fail to adapt to dynamic market trends.  

This project leverages Machine Learning (ML) techniques to predict football player market values using the FIFA 2023 dataset. We employ advanced data preprocessing, feature engineering, and a Random Forest regression model to provide a more accurate, scalable, and objective valuation system.  

## Tech Stack 
- Programming Language: Python   
- Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- Machine Learning Model: Random Forest Regressor    

### Model Selection & Evaluation 
The Random Forest Regressor was chosen due to its robustness, ability to handle categorical & continuous data, and built-in feature importance analysis.  

Evaluation Metrics:  
R² Score: The model achieved an R² score of 0.98, indicating high predictive power.
Root Mean Squared Error (RMSE): The RMSE was calculated as 1.1 million USD, signifying a low margin of error in valuation predictions.
Mean Absolute Error (MAE): The MAE was 397,000 USD, showing that, on average, the model's predicted values were very close to actual market values.

## Results & Insights
- Identified undervalued players with high potential
- Demonstrated correlation between release clause, wages & market value  
- Proved ML models outperform traditional valuation methods
