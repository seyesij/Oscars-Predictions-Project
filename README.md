# Oscars Prediction Project

Making predictions using Machine Learning. A Logistic Regression is used to predict the Oscar winners of the Best Picture category.

Used:

	* Python
	* Data visualization
	* Jupyter Notebook
	* Tableau
	* Machine Learning (Logistic Regression)
  
 ## Data
 The dataset is built from various public sources:
  * [Kaggle Oscars, Golden Globe, SAG, BAFTA datasets](https://www.kaggle.com/datasets/unanimad)
  * [Kaggle Oscar dataset](https://www.kaggle.com/datasets/matevaradi/oscar-prediction-dataset)
  * [IMDB dataset](https://www.imdb.com/interfaces/)
  * [Rotten Tomatoes dataset](https://www.kaggle.com/datasets/stefanoleone992/rotten-tomatoes-movies-and-critic-reviews-dataset)
 
 Data Preparation can be seen here: [Jupyter Notebook](https://github.com/seyesij/oscars_prediction_project/blob/main/data_preparation.ipynb)
 
### Data Visualization
An initial exploratory data analysis was performed using [Tableau](https://public.tableau.com/app/profile/adeseye.sijuwade/viz/OscarPredictionsAnalysis/Oscars_Prediction_Project)

### Model Training and Evaluation
- Input data: oscar nominees from 1960 to 2020 
- Define features and target values (X, y)
- Min-Max Scaling for numericals : for Train and Test set
- OneHotEncoding for categoricals : for Train and Test set
- Model : LogisticRegression
- Confusion Matrix
- Precision and Recall

## Conclusion
The model did good when predicting oscar winners, it had an accuracy of 93% with a precision score of 71% and recall score of 83%. The model was also tested on new data to predict the 2023 Academy Awards best picture winner. It accurately predicted Everything Everywhere All at Once as the winner. 

For future ideas we can look into adding more useful features to see if we can further improve the accuracy of our model.
