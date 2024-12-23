# NESA Course Specifications Linear Regression

This Jupyter Notebook collection is designed to support students understand the Linear Regression model defined in the [NESA Software Engineering Course Specifications](https://library.curriculum.nsw.edu.au/341419dc-8ec2-0289-7225-6db7f2d751ef/94e1eb0a-0df7-4dbe-9b72-5d5e0d17143a/software-engineering-11-12-higher-school-certificate-course-specifications.PDF) pg 28.

Several versions have been provided to support students understand the specification and apply it as a data engineer through the 'Model Development' and 'Operations' stages of the MLOps cycle.

![Course Specification MLOps Model](/images/MLOPS_Model.png)

> [!Important]
> This a corrected version of the course specifications. It is important that students see this model as an omnidirectional looping cycle (think complex design cycle). Particularly in the 'Model Development' stage students should expect to loop through the cycle many times before having a model ready for the operations stage. Or that it is identified design problem and cycle back in to the 'Design' stage before moving forward and again looping repeatedly through the 'Model Development' stage.

## 2. Model Development

### 2.1 Data Wrangling

1. The [Data Preprocessing Demonstration](/2.Model_Development/2.1.Data_Wrangling/2.1.1.data_preprocessing.ipynb) provides a demonstration of a basic data preprocessing using the Pandas library.
2. The [Data Wrangling Demonstration](7.data_wrangling.ipynb) provides a demonstration of wringling data to refine your machine learning model.

### 2.2 Feature Engineering

1. The [Feature Engineering Demonstration](/2.Model_Development/2.2.Feature_Engineering/2.2.1.feature_engineering.ipynb) blah blah

### 2.3 Model Training

1. The [Raw Demonstration](/2.Model_Development/2.3.Model_Training/2.3.1.raw_course_specification.ipynb) of the course specification provides a direct application (after debugging) of each step of the algorithm.
2. The [Graphical Demonstration](/2.Model_Development/2.3.Model_Training/2.3.2.graphical_course_specification.ipynb) of the course specifications provides graphs visualising each step of the algorithm.
3. The [CSV Demonstration](/2.Model_Development/2.3.Model_Training/2.3.3.CSV_course_specification.ipynb) of the course specifications uses a CSV upload of the data so larger model training data sets can be used.
4. The [SQL Demonstration](/2.Model_Development/2.3.Model_Training/2.3.4.SQL_course_specification.ipynb) of the course specifications imports the data from a SQL database so the data can be managed in a database.

### 2.4 Model Testing and Validation

1. The [Model Testing and Validation Demonstration](/2.Model_Development/2.4.Model_Testing_and_Validation/2.4.1.model_test_and_validate.ipynb) provides a number of ways to evaluate, test and validate your model using a second set of test data and then refine your model. This demonstration uses a different regression algorithm to the course specifications.

## Operations

### Deploying a Model

9. The [Export Import Demonstration](/3.Operations/3.1.Deploy_Model/3.1.1.export_import_course_specification.ipynb) of the course specifications exports the model so a separate Python implementation can use it to make predictions. The demonstration also includes how to save a Matplotlib image so it can be used in a UI.

   > [!Note]
   > There are some variations from the NESA course specifications to address syntax errors, missing methods and readability.

## Metalanguage

| Metalanguage      | Definition |
| ----------------- | ---------- |
| Linear Regression | ----       |
| Feature           | ----       |
| Target            | ----       |
| Prediction        | ----       |
| Model             | ----       |

Data wrangling
Data preprocessing
Feature Engineering
Cost
