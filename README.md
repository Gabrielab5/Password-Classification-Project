# Password Classification Project

## Project Overview
This project aims to classify passwords as either machine-generated or human-generated using various machine learning models. The project utilizes Python and libraries such as pandas, sklearn, etc.

## Features
The project includes feature engineering from the password strings to create a dataset that includes:
- Length of the password.
- Number of digits in the password.
- Number of letters in the password.
- Number of special characters in the password.

## Models Used
- Decision Tree Classifier
- Naive Bayes Classifier
- K-Nearest Neighbors Classifier (with k=3 and k=5)
- Support Vector Machine (SVM)

## Setup
To run this project, you will need Python installed on your system along with the following Python libraries:
- pandas
- sklearn

You can install the required libraries using pip:
```bash
pip install pandas scikit-learn

How to Run
Clone this repository to your local machine.
Ensure you have the required Python libraries installed.
Run the script password_check.py.
Data
The data used in this project (passwords.csv) contains passwords labeled according to their strength:

0 or 1 indicating human-generated passwords.
2 indicating machine-generated passwords.
The data should be placed in the same directory as the script or adjusted accordingly within the script to point to the correct data path.

Contributing
Feel free to fork the repository and submit pull requests.

License
This project is licensed under the MIT License - see the LICENSE file for details.
