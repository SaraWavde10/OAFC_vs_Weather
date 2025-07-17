# Is Oldham Athletic Resistant to Cold Weather?

This project investigates whether weather conditions (temperature, wind, humidity, etc.) influence match outcomes for Oldham Athletic AFC - inspired by the club's home stadium, Boundary Park, being known as one of the coldest in English football. The dataset consisted of over 1500 matches, and weather from 11,000+ days that was used for this project. 

## Hypothesis

Cold, windy conditions may favour Oldham due to familiarity and resilience developed during training and home games.

## Dataset

* Match data: Historical fixtures and results for Oldham Athletic
* Weather data: Matched by date and location using external weather records

## Tools and Technologies

* Python (pandas, numpy, matplotlib)
* scikit-learn
* xgboost
* Random Forest

## Workflow

1. Data cleaning and merging match data with weather records
2. Correlation matrix for initial exploration of variable relationships
3. Feature selection and label encoding
4. Training machine learning models:

   * RandomForestClassifier
   * XGBClassifier
5. Model evaluation using accuracy scores and confusion matrices

## Results

* Weather variables showed no significant correlation with match outcome
* Machine learning models trained on weather data alone failed to meaningfully predict win/loss/draw
* The initial hypothesis was not supported by the data

## Key Learnings

* Exploratory data analysis and model building must be grounded in evidence, not assumption
* Null results are valid and valuable when backed by clear methodology
* Gained experience in working with real-world data, feature engineering, and supervised machine learning

## Possible Extensions

* Incorporate team-level statistics (e.g., form, injuries, player availability)
* Explore interaction effects (e.g., weather conditions versus away team performance)
* Use data from additional seasons or include more granular weather metrics
