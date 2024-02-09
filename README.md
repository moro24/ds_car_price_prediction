## Project Description
The aim of this project is to develop a machine learning model that can accurately predict the price of a car based on various features such as make, model, mileage, year, and other relevant factors. The project will involve collecting a dataset of car listings with associated prices and features from online sources or existing databases. Data preprocessing steps will be implemented to clean and prepare the dataset for modeling, including handling missing values, encoding categorical variables, and scaling numerical features.

Next, various machine learning algorithms such as linear regression, decision trees, random forests, and gradient boosting will be trained and evaluated using techniques like cross-validation and hyperparameter tuning to identify the best-performing model. Feature importance analysis will also be conducted to understand which features have the most significant impact on the predicted car prices.

The developed model will be deployed into a user-friendly interface, allowing users to input car features and obtain a predicted price estimate. Additionally, the project will include documentation detailing the steps involved in data collection, preprocessing, modeling, evaluation, and deployment, making it accessible for others to understand and replicate.

## Dataset Description 

### Dataset Url 
- ttps://www.kaggle.com/datasets/deepcontractor/car-price-prediction-challenge

### Attributes
- ID
- Price: price of the care(Target Column)
- Levy
- Manufacturer
- Model
- Prod. year
- Category
- Leather interior
- Fuel type
- Engine volume
- Mileage
- Cylinders
- Gear box type
- Drive wheels
- Doors
- Wheel
- Color
- Airbags


## Environment Configuration
- Installing virtual Env
    - pip install pipenv 

- Installing Packages
    - pipenv install jupyter notebook pandas numpy matplotlib seaborn scikit-learn xgboost 

- Starting Virtual Env
    - pipenv shell 

- Starting Notebook
    - jupyter-notebook