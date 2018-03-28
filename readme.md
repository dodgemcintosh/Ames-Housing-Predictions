<img src="http://imgur.com/1ZcRyrc.png" style="float: left; margin: 20px; height: 55px">

# Ames Housing Pricing Predictions

_Author: Dodge McIntosh_

---

The goal for this project is two-fold:

1. Creating and iteratively refining regression and classification models
2. Using [Kaggle](https://www.kaggle.com/) to practice the modeling process

I was tasked with creating two models with the highest possible accuracy based on the Ames Housing Dataset. Those models will predict the following:

- The price of a house at sale (regression)
- Whether a house sale was abnormal or not (classification)

## Data Context

The Ames Housing Dataset is an exceptionally detailed and robust dataset with over 70 columns of different features relating to houses. While the two models I made  predicted different targets (and required different features, model choices, and hyperparameters), I was able to use the knowledge I developed from generating one model to help inform the other (and vice versa)!

Additionally, our class hosted two competitions on Kaggle (one for the regression and one for the classification) in order to practice the following skills:

- Refining models over time
- Use of train-test split, cross-validation, and data with unknown values for the target to simulate the modeling process
- The use of Kaggle as a place to practice data science

## Modeling Process Overview

1. The train and test datasets for both challenges are the **same**, with the exception of the target that I was trying to predict.
2. The train dataset has all of the columns that I needed to generate and refine the models. The test dataset has all of those columns except for the two targets that I was trying to predict in my Regression and Classification models.
3. Generated my regression and classification models using the training data. Within this process, I made use of:
    - train-test split
    - cross-validation / grid searching for hyperparameters
    - strong exploratory data analysis to question correlation and relationship across predictive variables
    - code that reproducibly and consistently applies feature transformation (such as the preprocessing library)
4. Predicted the values for target columns in the test dataset and submitted my predictions to Kaggle to see how my model performed against unknown data.
    - **Note**: Kaggle expects to see submissions in a specific format. I needed to check the challenge's page to make sure I was formatting files correctly.

## Submission Checklist

These are the following deliverables that I submitted for the project:

1. Code for the regression and classification models, including exploratory data analysis.
2. Multiple successful prediction submissions on the private, in-class, Kaggle competition for the regression model.
3. Multiple successful prediction submissions on the private, in-class, Kaggle competition for the classification model.

## Project Feedback + Evaluation

For this project, I wanted to make sure I was adhering to the following principles throughout:

- **Organization**:	Clearly commented, annotated and sectioned Jupyter notebook or Python script. Comments and annotations add clarity, explanation and intent to the work. Notebook is well-structured with title, author and sections. Assumptions are stated and justified.
- **Exploratory Data Analysis**: A thorough exploratory data analysis has been conducted. Descriptive statistics, univariate and bivariate analysis, and plotting are skillfully used to explore connections across the dataset between features and targets.
- **Modeling Process**: Skillful and correct use of cross-validation, grid search, and goodness-of-fit metrics to evaluate candidate models. Assumptions and decisions in the modeling process are stated and justified. Use of correct modeling techniques in each challenge. Data is reproducibly and reliably transformed between training and test datasets.

## Questions and Connections

Find me on [LinkedIn](https://www.linkedin.com/in/dodgemcintosh/) to share your tips and tricks, ask me any questions, or if you just want to connect!