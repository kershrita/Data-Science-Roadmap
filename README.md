# Welcome to Data Science World!

**Data Science** is an interdisciplinary field that combines various techniques, algorithms, processes, and systems to extract valuable insights and knowledge from data. It encompasses data analysis, machine learning, statistical modeling, and domain expertise to interpret and solve complex problems. 

**Data scientists** work with large and diverse datasets, using their skills to uncover patterns, trends, and information that can inform data-driven decisions, business strategies, and scientific research. In essence, data science empowers organizations and individuals to leverage data as a valuable resource for making informed choices and predictions.

![Data Science Pipeline](images/data-science-pipeline.png)

##  Recommended Background

Strongly recommend that students have experience with `Python`, ideally some background of `machine learning`, in `probability and statistics`, and `linear algebra`.

If you do not have a background in these areas, take some resources to learn:
- **Python**: ...
- **Machine Learning**: ...
- **Probability and Statistics**: ...
- **Linear Algebra**: ...

## Learning Objectives (updatable)
After taking this course, you should:

- Understand the end-to-end data science pipeline, from data collection to model deployment.
- Be familiar with the programming tools and libraries required to execute different phases of data science projects.
- Demonstrate the ability to collect data from a variety of sources, including structured and unstructured data.
- Know how to explore and visualize datasets, gaining insights into data distributions, patterns, and outliers.
- Be proficient in conducting data analysis using a range of statistical and machine learning techniques.
- Create data-driven reports and presentations that convey insights in a clear and compelling manner, addressing the needs of different audiences.

## Topics Covered (updatable)

### Data Preparation:
1. **Gather**:
    - **Data Collection:** SQL, NoSQL, and Web Scrapping.
    - **Data Integration:** Merge data from various sources.

2. **Discover**:
    - **Exploratory Data Anlysis (EDA)**: Focus on libraries such as Matplotlib, Seaborn, and Plotly Express to create relevant plots for data exploration.

3. **Cleanse**:
    - **Data Cleaning**:
      - Handling missing values (imputation).?
      - Removing duplicates.
      - Multiple fields in a single column.
      - Non-unique column headers.
    - **Data Transformation**: Standardize data formats, units, or scales to ensure consistency.
    - **Data Balancing**: Oversampling and Undersampling to ensure consistency.

4. **Transform**:
    - **Feature Engineering**: Create new features from existing ones, e.g., one-hot encoding, scaling, and dimensionality reduction.
    - **Aggregation**: Summarize data at different granularities, e.g., aggregating sales data by day, week, or month.

5. **Store**:
    - **Data Warehouse**: Store cleaned in a data warehouse for efficient retrieval and analysis.

### Machine Learning:
  - **Machine Learning Overview**:
    - Supervised and Unsupervised Learning
    - LazyPredict, catboost, etc..
  - **Hyperparameter Tuning**: Grid Search and Optuna for optimizing model parameters
  - **Ensemble Methods**: Bagging, Boosting, Voting, Staking, etc..
  - **Model Evaluation**: Evaluation metrices for classification, regression, and clustering.

### Deployment and Communication:
  - Cover machine learning model deployment with options like cloud services (Microsoft Azure).
  - Emphasize clear and concise communication through data-driven reports and presentations.

## Plan Outline

### Week 1: Introduction to Data Science and Statistics
- **Session 1**: Introduction to Data Science
  - Overview of data science as a field.
  - The data science pipeline and its stages.
  - Basic concepts, key terms.

- **Session 2**: Introduction to Statistics
  - Definition of statistics and its importance in data science.
  - The role of statistics in data analysis, interpretation, and decision-making.
  - Types of data (Qualitative, Quantitive).
  - Descriptive Statistics, Probability, Distributions ...
  - Basic plots for visalizations to gain insights about data.
  - Assignment: Statistics questions sheet.

### Week 2: Data Collection and Data Cleaning
- **Session 3**: SQL Data Collection and Initial Data Insights
  - Introduction to data collection & data integration.
  - Data collection from SQL databases using Python and libraries like sqlite.
  - Basic data exploration and initial insights from the data using Pandas.
  - Basic data visualization using matplotlib.
  - Hands-on exercise: Data collection from SQL database with data exploration using Pandas.
  - Assignment: Practice example with SQL.

- **Session 4**: SQL Data Refresher and Data Cleaning
  - Recap on Data collection from SQL databases.
  - The importance of data cleaning and handling missing data.
  - Techniques for handling missing values (imputation).
  - Basic data visualization using matplotlib (cont).
  - Data Transformation (handle columns distributions).
  - Hands-on exercise: Data collection from SQL database with handling missing data.
  - Assignment: Practice example with SQL.

### Week 3: Data Preparation and Feature Engineering
- **Session 5**: NoSQL Data Collection and Transformation
  - Data collection from NoSQL mongoDB database.
  - More data cleaning, exploration using pandas.
  - Basic data visualization using seaborn.
  - Data Transformation, check data formats, units, scales, etc...
  - Hands-on exercise: Data collection from SQL database with data transformation and feature engineering
  - Assignment: Practice example with SQL.

- **Session 6**: Advanced Data Cleaning and Feature Engineering
  - More data cleaning, exploration using pandas.
  - Feature engineering, columns aggregation.
  - Data balancing using oversampling and undersampling.
  - Basic data visualization using seaborn (cont).
  - Hands-on exercise: Practical application of data cleaning and feature engineering.
  - Assignment: ...


### Week 4: Advanced Data Collection and Storage
- **Session 7**: Web Data Scrapping and Visualization
  - Data collection using web scrapping.
  - More data cleaning, exploration using pandas.
  - Basic data visualization using plotly express.
  - Hands-on exercise: Load data using web scrapping exercise.
  - Assignment: Practice example with web scrapping.

- **Session 8**: Advanced Data Cleaning and Storage
  - More data cleaning, exploration using pandas.
  - Basic data visualization using plotly express (cont).
  - Store data in data warehouse, e.g. CSV, database.
  - Hands-on exercise: Practical application of feature scaling and engineering.
  - Assignment: ..

### Week 5: Supervised Machine Learning
- **Session 9**: Machine Learning Basics and Classification
  - Introduction to machine learning and its types.
  - Supervised learning: Concepts and applications.
  - LazyPredict classifier for quick model selection.
  - Hyperparameter tunning using gridsearch.
  - Communicating results and evaluation metrices for classification problem.
  - Hands-on exercise: Implement a classification model using LazyPredict.
  - Assignment: ...

- **Session 10**: Regression Problem
  - LazyPredict regressor for quick model selection.
  - Hyperparameter tunning using gridsearch.
  - Communicating results and evaluation metrices for regression problem.
  - Hands-on exercise: Implement a regression model using LazyPredict.
  - Assignment: ..

### Week 6: Advanced Machine Learning Techniques
- **Session 11**: Unsupervised Learning and Clustering
  - Unsupervised learning: Concepts and applications.
  - K-means clustering algorithm.
  - PCA dimensionality reduction for plot clusters.
  - Communicating results and evaluation metrices for clustering problem.
  - Hands-on exercise: Implement a cluster model.
  - Assignment: ...

- **Session 12**: Ensemble Methods and Advanced Optimization
  - Ensemble methods for classification and regression.
  - Catboost algorithm for categorical data.
  - Hyperparameter tunning using optuna.
  - Hands-on exercise: Implement ensemble methods and optimize models.
  - Assignment: ..
  - 
### Week 7

### Week 8

## Feedback

Your feedback is invaluable! If you have suggestions, questions, or find issues with the materials, please open an issue or contact me at ashrafabdulkhaliq80@gmail.com.
