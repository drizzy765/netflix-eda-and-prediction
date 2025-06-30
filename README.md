# Netflix Data Analysis and Content Prediction Project

This project involves exploring and analyzing Netflix's content catalog, with the goal of uncovering insights and building predictive models. Using machine learning and NLP, the notebook focuses on understanding what makes a show successful and how Netflix content evolves over time.

## Objectives

- Perform exploratory data analysis on Netflix's dataset
- Clean and preprocess text and categorical data
- Predict the main genre of a title using its description (NLP)
- Predict if a show or movie is likely to be a "hit"
- Predict the month a show is most likely to be released

## Dataset

The dataset contains metadata of Netflix content, including:
- Title, cast, director, rating
- Description and genre tags
- Date added and release year

## Workflow

1. **Data Cleaning**
   - Missing values handled for cast, director, and country
   - Text fields cleaned and standardized
   - Duration parsed and converted to numerical form
   - Release month extracted from date

2. **Exploratory Data Analysis**
   - Most common genres and ratings
   - Content trends by year and month
   - Distribution by type and country

3. **Modeling Tasks**
   - Genre Prediction (Multinomial Naive Bayes using TF-IDF)
   - Hit Prediction (Random Forest Classifier)
   - Release Month Prediction (Gradient Boosting Regressor)

## Results

- Genre prediction accuracy: 36.2%
- Hit prediction accuracy: 71.3%
- Release month regression RMSE: 3.45

## Future Improvements

- Use deep learning models (e.g., BERT) for genre classification
- Improve hit definition using external sources (e.g., IMDb scores)
- Deploy results in an interactive Streamlit dashboard

## Tools and Libraries

- Python, Pandas, NumPy
- Scikit-learn, LightGBM
- Seaborn, Matplotlib
- Natural Language Processing with TF-IDF

## Author

[Agoro Oluwatimilehin]  
[agorooluwatimilehin05@gmail.com]

