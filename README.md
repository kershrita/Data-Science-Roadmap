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
  - Importance of data science and it's tools.
  - Basic concepts, key terms.

- **Session 2**: Introduction to Statistics for Data Science
  - Introduction to statistics and its importance in data science.
  - Types of data (Qualitative, Quantitive).
  - Descriptive and inferential statistics.
  - Basic plots for visalizations to gain insights about data.
  - Make decision in data science based on statistics.
  - Assignment: Practice example on descriptive statistics.

### Week 2: Diamonds
- **Session 3**: Introduction to SQL
  - Data collection from SQL database using SQLite Python.
  - Basic data exploration using pandas.
  - Basic data visualization using matplotlib.
  - Hands-on exercise: Data exploration & visualization from diamonds database.
  - Assignment: Data exploration & visualization from flights database.

- **Session 4**: Handle Missing Values
  - The importance of data cleaning and handling missing data.
  - Techniques for handling missing values (imputation).
  - How to choose the right imputation method.
  - More data exploration using pandas.
  - Hands-on exercise: Handle missing values from planets database.
  - Assignment: ...

### Week 3: Feature Engineering
- **Session 5**: Data Transformation
  - Handle columns distributions.
  - Check data formats, data splitting, units, scales, etc...
  - Data balancing using oversampling and undersampling.
  - Basic data visualization using seaborn.
  - Hands-on exercise: Apply data transformation on planets database.
  - Assignment: ...

- **Session 6**: Feature Selection
  - Types of data.
  - Feature Selection Approaches.
  - Feature Selection vs. Other Technologies & Methodologies
  - Basic data visualization using seaborn (cont).
  - Hands-on exercise: ...
  - Assignment: ...

`
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
`

### Week 4: Machine Learning
- **Session 7**: Machine Learning Overview
  - Introduction to machine learning.
  - Types of machine learning
  - Distance-based, probability-based, and tree-based algorithms.
  - Evaluation metrices to measure algorithm performance.
  - Hands-on exercise: ...
  - Assignment: ...

- **Session 8**: Regression Problem
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

### Week 7: Reviewing and Applying Previous Concepts
- **Session 13**: Data Collection and Exploration
    - Apply the chosen technique to gather a dataset.
    - Perform exploratory data analysis (EDA) on the collected dataset using libraries like Matplotlib, Seaborn, or Plotly Express.
    - Create meaningful visualizations to gain insights about the data.
    - Discuss the challenges and discoveries during the data collection and exploration process.
    - Assignment: ...

- **Session 14**: Modeling and Evaluation
    - Review machine learning algorithms previously covered.
    - Build and evaluate machine learning models using the collected and explored data.
    - Discuss the selection of appropriate evaluation metrics for the given problem.
    - Fine-tune the models and apply optimization techniques, such as hyperparameter tuning.
    - Discuss the model's performance and its implications for the dataset.
    - Assignment: ...

### Week 8: Deployment and Communication
- **Session 15**: Presentation and Communication*
    - Cover the essentials of presenting data-driven insights to stakeholders.
    - Discuss the importance of clear and concise communication.
    - Addressing the needs of different audiences, including technical and non-technical stakeholders.
    - Showcase best practices for creating data-driven reports and presentations.
    - Present student projects as examples of effective data communication.
    - Assignment: ...

- **Session 16**: ...

## Feedback

Your feedback is invaluable! If you have suggestions, questions, or find issues with the materials, please open an issue or contact me at ashrafabdulkhaliq80@gmail.com.
