# neural-network-challenge-1
Module 18 Challenge - Neural Network Challenge

## Background
You work at a company that specializes in student loan refinancing. If the company can predict whether a borrower will repay their loan, it can provide a more accurate interest rate for the borrower. Your team has asked you to create a model to predict student loan repayment.

The business team has given you a CSV file that contains information about previous student loan recipients. With your knowledge of machine learning and neural networks, you decide to use the features in the provided dataset to create a model that will predict the likelihood that an applicant will repay their student loans. The CSV file contains information about these students, such as their credit ranking.

## Files

## Before You Begin
Before starting the assignment, be sure to complete the following steps:
   - [x] Create a new repository for this project called `neural-network-challenge-1`. **Do not add this homework assignment to an existing repository.**
   - [x] Clone the new repository to your computer.
   - [x] Inside your local Git repository, add the starter file `student_loans_with_deep_learning.ipynb` from your file downloads.
   - [x] Push these changes to GitHub.
   - [x] Upload `student_loans_with_deep_learning.ipynb` to Google Colab and work on your solution there.
        - To track your version history, periodically download your file and push the changes to your repository.

## Instructions

Open the starter file in Google Colab and complete the following steps, which are divided into four parts:

- Prepare the data for use on a neural network model.

- Compile and evaluate a model using a neural network.

- Predict loan repayment success by using your neural network model.

- Discuss creating a recommendation system for student loans.

## Part 1: Prepare the data for use on a neural network model

Using your knowledge of Pandas and scikit-learn’s `StandardScaler()`, preprocess the dataset so that you can use it to compile and evaluate the neural network model later.

Open the starter code file and complete the following data preparation steps:

1. Read the data from https://static.bc-edx.com/ai/ail-v-1-0/m18/lms/datasets/student-loans.csv into a Pandas DataFrame. Review the DataFrame, looking for columns that could eventually define your features and target variables.

2. Create the features `(X)` and target `(y)` datasets. The target dataset should be defined by the “credit_ranking” column. The remaining columns should define the features dataset.

3. Split the features and target sets into training and testing datasets.

4. Use scikit-learn's `StandardScaler` to scale the features data.

## Part 2: Compile and Evaluate a Model Using a Neural Network
Use your knowledge of TensorFlow to design a deep neural network model. This model should use the dataset’s features to predict the credit quality of a student based on the features in the dataset. Consider the number of inputs before determining the number of layers that your model will contain or the number of neurons on each layer. Then, compile and fit your model. Finally, evaluate the model to calculate its loss and accuracy.

To do so, complete the following steps:

1. Create a deep neural network by assigning the number of input features, the number of layers, and the number of neurons on each layer using TensorFlow’s Keras.

### HINT
You can start with a two-layer deep neural network model that uses the `relu` activation function for both layers.

2. Compile and fit the model using the binary_crossentropy loss function, the adam optimizer, and the accuracy evaluation metric.

### HINT
When fitting the model, start with a small number of epochs, such as 50 or 100.

3. Evaluate the model using the test data to determine the model’s loss and accuracy.

4. Save and export your model to a keras file, and name the file `student_loans.keras`.

### NOTE
Remember to download your saved model from Colab so you can upload it to your GitHub repo.

## Part 3: Predict loan repayment success by using your neural network model

Use the model you saved in the previous section to make predictions on your reserved testing data.

To do so, complete the following steps:

1. Reload your saved model.

2. Make predictions on the testing data, saving them to a DataFrame and rounding the predictions to binary values.

3. Generate a classification report with the predictions and testing data.

## Part 4: Discuss creating a recommendation system for student loans

Briefly answer the following questions in the space provided:

1. Describe the data that you would need to collect to build a recommendation system to recommend student loan options for students. Explain why this data would be relevant and appropriate.

2. Based on the data you chose to use in this recommendation system, would your model be using collaborative filtering, content-based filtering, or context-based filtering? Justify why the data you selected would be suitable for your choice of filtering method.

3. Describe two real-world challenges that you would take into consideration while building a recommendation system for student loans. Explain why these challenges would be of concern for a student loan recommendation system.

## Hints and Considerations
- Review previous modules if you need help with data preprocessing.

- Make certain that your training and testing data are preprocessed in the same ways.

## Badges

## Visuals

## Installation

## Usage

## Support
Some of the code on this assigment was done with the help of a bootcamp tutor.

## Roadmap

## Contributing

## Authors and acknowledgment
1. Reference material - [PEP 8 – Style Guide for Python Code](https://peps.python.org/pep-0008/)
2. Python HOWTOs - [https://docs.python.org/3/howto](https://docs.python.org/3/howto/index.html)
3. This site was built using [GitHub Pages](https://pages.github.com/)

## License
Apache License
Version 2.0, January 2004

## Project status
- 

## Footnotes