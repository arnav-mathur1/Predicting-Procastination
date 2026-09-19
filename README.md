# Predicting Procrastination in College Courses Using Machine Learning
Project for Aspiring Scientists Summer Internship Program (ASSIP) at George Mason University (GMU), Summer 2023

Conducted the research under [Dr. Mihai Boicu](https://mason.gmu.edu/~mboicu/)

# Overview
## Data
- Processed student data points using Python and Pandas
- Used features including:
  - Assignment type
  - Number of attempts
  - Grades
  - Submission time
- Created a procrastination index based on:
  - Late submissions
  - Grade improvement across attempts

## Models

Trained and compared three models:

- **Random Forest Model**
  - 100 decision trees

- **Support Vector Regression**
  - RBF kernel

- **Neural Network**
  - 32-neuron input layer
  - 16-neuron hidden layer
  - ReLU activations
  - 100 epochs
  - Batch size of 32

The data was split into **80% training and 20% testing**.

## Results

| Model | R² | MSE |
|---|---:|---:|
| Random Forest | **0.873** | **0.0129** |
| Neural Network | 0.840 | 0.0163 |
| Support Vector Regression | 0.609 | 0.0397 |

The **Random Forest model performed best**, achieving an R² of approximately **0.87**.


## Tools
Python, Pandas, scikit-learn, Keras

# Files
Added in the Jupyter notebooks used to execute the project work. With the help of Claude Code, I was able to include a file summary of each of the files to explain how it contributed to the final research.

# Links

[Informal Research Paper](https://docs.google.com/document/d/1XrM7j1MKhAPYrMlUbeS1CZprwignAMuoTLS5A2KJvzg/edit?usp=sharing)

[Final Project Presentation](https://drive.google.com/file/d/1xDpBevk_NPJZxU_GdDTnBzp-x6i60Dep/view?usp=sharing)

[Published Abstract in the GMU Libary](https://journals.gmu.edu/jssr/article/view/3848)
