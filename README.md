# Nba-games-prediction

This Data Science Project from scratch is a real-life data science project, end-to-end.
It consists of Building a predictive model of nba games, deploying it with FastAPI and creating a web app with Dash 

Step-by-step process

## Part 1: Brainstorm ideas

- The first step in the project was to brainstorm ideas for what the model could be used for. Some potential applications included creating a tool for fans to make their own predictions, helping teams make strategic decisions, and predicting the outcomes of betting markets.

- After considering a variety of options, we decided to focus on creating a tool for fans to make and compare their own predictions. This would be a fun and engaging way to involve users in the model, and it would also provide a useful benchmark for evaluating the model's performance.

## Part 2: Collect data (NBA games)

- The first step in this project was to gather and prepare the data. We obtained a dataset of past NBA games from the 2015-2016 season to the 2019-2020 season from a publicly available source. This dataset included various statistics for each game, such as the score, location, and team statistics.

## Part 3: Clean and Explore data (feature engineering)

- The data was preprocessed to remove any irrelevant or missing information and to ensure that it was in a suitable format for building the predictive model. This involved tasks such as handling missing values, normalizing numerical data, and encoding categorical data.

## Part 4: Build a predictive model

- Once the data was prepared, the next step was to train a predictive model on it. A variety of machine learning algorithms were tested, including decision trees, random forests, and support vector machines. The model was trained and evaluated using a variety of metrics such as accuracy, precision, and recall.

- After comparing the performance of the different algorithms, the random forest model was selected as the best performer. It was able to achieve an accuracy of approximately 70% on the test set, which is considered to be good for this type of problem.

## Part 5: Deploy the model with FastAPI

- Once we had trained a satisfactory predictive model, we needed to deploy it as a web application so that users could interact with it. We used FastAPI to create a REST API for the model, which allowed us to host the model on a server and make predictions using simple HTTP requests.

## Part 6: Create a web app with Dash

- We also used Dash to create a web app that allowed users to input their own predictions and compare them to the model's predictions. The app also displayed some basic information about the model and provided some visualizations of the prediction results.

Technologies that will be used

☑️ JupyterLab (Notebook)

☑️ PyCharm

☑️ Python (including pandas, scikit-learn, xgboost, Dash, etc)

☑️ FastAPI


