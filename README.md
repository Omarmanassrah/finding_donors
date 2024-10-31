# CharityML Income Prediction
This project uses machine learning techniques to predict whether an individual earns more than $50,000 per year based on data from the U.S. Census Bureau. This project is part of the Finding Donors for CharityML initiative, aimed at helping non-profits better target potential donors by identifying high-income individuals.

Project Overview
CharityML's goal is to increase the efficiency of outreach by focusing on high-income individuals who are more likely to contribute. In this project, I use a range of supervised learning algorithms to identify income levels, evaluate model performance, and select the best model for deployment. After training and optimizing models on census data, we achieve a final solution that balances accuracy, efficiency, and interpretability.

Install
This project requires Python 2.7 and the following Python libraries installed:

NumPy
Pandas
matplotlib
scikit-learn
You will also need to have software installed to run and execute an iPython Notebook

We recommend students install Anaconda, a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.

Code:
The main code for this project is located in the finding_donors.ipynb notebook file. Additional supporting code for visualizing the necessary graphs can be found in visuals.py. Additionally, the Report.html file contains a snapshot of the main code in the jupyter notebook with all code cells executed.

Run:
In a terminal or command window, navigate to the top-level project directory finding_donors/ (that contains this README) and run one of the following commands:
jupyter notebook finding_donors.ipynb

Data
The modified census dataset consists of approximately 32,000 data points, with each datapoint having 13 features.
Features

age: Age
workclass: Working Class (Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked)
education_level: Level of Education (Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool)
education-num: Number of educational years completed
marital-status: Marital status (Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse)
occupation: Work Occupation (Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces)
relationship: Relationship Status (Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried)
race: Race (White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black)
capital-gain: Monetary Capital Gains
capital-loss: Monetary Capital Losses
hours-per-week: Average Hours Per Week Worked






