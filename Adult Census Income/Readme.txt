
#### Problem :
The data for the case study comes from the Census Income data set in the UCI Machine Learning Repository. Objective is to predict whether income of an individual exceeds $50K/per year based on census data.

#### DataSet:
http://archive.ics.uci.edu/ml/datasets/Adult


#### Data Dictionary :
age: continuous.
workclass: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.
final weight: continuous.
education: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.
education-num: continuous.
marital-status: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.
occupation: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.
relationship: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.
race: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black.
sex: Female, Male.
capital-gain: continuous.
capital-loss: continuous.
hours-per-week: continuous.
native-country: United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands.


#### Folder Contents
        > Folder contains a ipynb notebook  
        > Data set


#### NoteBook Contents & Summary 
            > 1. Data Overview / Exploration
            		- Data Types
            		- Missing Values 
            		- Target Variable Information
            > 2. Numerical Features Univariate Distribution
            		- Figures
            		- Histogram
            > 3. Correlation Analysis Features (Numeric Features)
            > 4. Bivariate Distributions : Target Variable with respect to Numerical Features
            		- KDE Plot 
            > 5. Categorical Features Univariate Distribution Analysis
            		- Counts
            		- Bar Chart
            > 6. Bivariate Distributions : Target Variable with respect to Categorical Features
            		- Bar Chart
            > 7. Data Preparation for Model
                        - Cast Object to Category for Light Gradient Boost Method Model 
                        - Data Split into Development and Validation Sample
            > 8. Model Building             
                Selected two models which can handle and allows numerical and categorical variables so there is no requirement of encoding categorical variables:
                     1. H2O Random Forest 
                     2. Light Gradient Boosting Machine (LGBM) 



#### Next Steps: 
        Additional Exploratory Steps can performed further 
        (I've currently skipped these as I was getting decent results, however, given time, we can explore the following out too): 
          	> Transform Various Categorical variables into bins e.g., Country variable could be binned into United States and Others    
                > Perform hyperparameter tuning using GridSearchCV
                > Experiment with different probability cutoffs for optimized results
                > Explore relationships between Numeric and Categorical Variables
                > Derive more features from existing features
