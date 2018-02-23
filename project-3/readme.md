# Project 3 - Ames Housing Data and Kaggle Challenges

Due Date: November 8, 2017

Welcome to Project 3! In this project, we are hoping to use this project to give you a chance to practice two important skills:

1. Creating and iteratively refining regression and classification models
2. Using [Kaggle](https://www.kaggle.com/) to practice the modeling process

You are tasked with creating two models with the highest possible accuracy based on the Ames Housing Dataset. Those models will predict the following:

- The price of a house at sale (regression)
- Whether a house sale was abnormal or not (classification)

The Ames Housing Dataset is an exceptionally detailed and robust dataset with over 70 columns of different features relating to houses. While the two models you make will predict different targets (and will require different features, model choices, and hyperparameters), you will be able to use the rich knowledge you develop from generating one model to help inform the other (and vice versa!)

Secondly, we are hosting two competitions on Kaggle (one for the regression and one for the classification) to give you the opportunity to practice the following skills:

- Refining models over time
- Use of train-test split, cross-validation, and data with unknown values for the target to simulate the modeling process
- The use of Kaggle as a place to practice data science

## Set-up

Before you begin working on this project, please do the following:

1. Sign up for an account on [Kaggle](https://www.kaggle.com/)
2. Review the material on the [DSI-EAST-1 Regression Challenge](https://www.kaggle.com/c/dsi-east-1-regression)
3. Review the material on the [DSI-EAST-1 Classification Challenge](https://www.kaggle.com/c/dsi-east-1-classification)

## The Modeling Process

1. The train and test datasets for both challenges are the **same**, with the exception of the target that you are trying to predict.
2. The train dataset has all of the columns that you will need to generate and refine your models. The test dataset has all of those columns except for the two targets that you are trying to predict in your Regression and Classification models.
3. Generate your regression and classification models using the training data. We expect that within this process, you'll be making use of:
    - train-test split
    - cross-validation / grid searching for hyperparameters
    - strong exploratory data analysis to question correlation and relationship across predictive variables
    - code that reproducibly and consistently applies feature transformation (such as the preprocessing library) 
4. Predict the values for your target columns in the test dataset and submit your predictions to Kaggle to see how your model does against unknown data. 
    - **Note**: Kaggle expects to see your submissions in a specific format. Check each challenge's page to make sure you are formatting your files correctly!

## Submission Checklist

We expect the following to be submitted by end of day on the due date. 

1. Your code for the regression and classification models, including your exploratory data analysis, submitted via pull request to this repository.
2. At least one successful prediction submission on [DSI-EAST-1 Regression Challenge](https://www.kaggle.com/c/dsi-east-1-regression) --  you should see your name in the "Leaderboard" tab.
3. At least one successful prediction submission on [DSI-EAST-1 Classification Challenge](https://www.kaggle.com/c/dsi-east-1-classification) -- you should see your name in the "Leaderboard" tab.
4. Check the Project Feedback + Evaluation section to ensure that you know what will factor into the evaluation of your work.

## Project Feedback + Evaluation

For all projects, students will be evaluated on a simple 4 point scale (0-3 inclusive). Instructors will use this rubric when scoring student performance on each of the core project requirements:

Score | Expectations
----- | ------------
**0** | _Does not meet expectations. Try again._
**1** | _Approaching expectations. Getting there..._
**2** | _Meets expecations. Great job._
**3** | _Surpasses expectations. Brilliant!_

For Project 3 the evaluation categories are as follows:

- **Organization**:	Clearly commented, annotated and sectioned Jupyter notebook or Python script. Comments and annotations add clarity, explanation and intent to the work. Notebook is well-structured with title, author and sections. Assumptions are stated and justified.
- **Exploratory Data Analysis**: A thorough exploratory data analysis has been conducted. Descriptive statistics, univariate and bivariate analysis, and plotting are skillfully used to explore connections across the dataset between features and targets. 
- **Modeling Process**: Skillful and correct use of cross-validation, grid search, and goodness-of-fit metrics to evaluate candidate models. Assumptions and decisions in the modeling process are stated and justified. Use of correct modeling techniques in each challenge. Data is reproducibly and reliably transformed between training and test datasets.
- **Regression Challenge Submission**: Student has made at least one successful submission to the [DSI-EAST-1 Regression Challenge](https://www.kaggle.com/c/dsi-east-1-regression)
- **Classification Challenge Submission**: Student has made at least one successful submission to the [DSI-EAST-1 Classification Challenge](https://www.kaggle.com/c/dsi-east-1-classification)