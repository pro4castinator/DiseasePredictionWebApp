# Multiple Disease Prediction System

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://multiple-disease-pred.streamlit.app/)

A web-based application for predicting multiple diseases using Machine Learning models.

## Table of Contents

- [About](#about)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Models](#models)
- [Built With](#built-with)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## About

The Multiple Disease Prediction System is a Streamlit web application that allows users to predict three different diseases: Diabetes, Heart Disease, and Parkinson's Disease. The application uses Machine Learning models trained on relevant datasets to provide predictions based on user input.

## Demo

Try out the live demo: [Multiple Disease Prediction System](https://multiple-disease-pred.streamlit.app/)

## Installation

To run the application locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/your_username/your_project.git
cd your_project
```
2. Install the required dependencies:

```bash
pip install -r requirements.txt
```
3. Run the application:

```bash
streamlit run app.py
```


## Usage

After running the application, a web page will open in your default browser.

Use the sidebar to navigate between different disease prediction pages.

Enter the required information in the input fields.

Click the corresponding "Test Result" button to get the disease prediction.

## Features

- Predict Diabetes: Enter details like the number of pregnancies, glucose level, blood pressure, etc., to predict whether a person has diabetes or not.
- Predict Heart Disease: Provide information about age, sex, chest pain types, resting blood pressure, etc., to predict the likelihood of heart disease.
- Predict Parkinson's Disease: Input various speech-related features to predict the presence of Parkinson's disease.

## Models

The application uses the following pre-trained machine learning models:

- Diabetes Prediction: Saved as 'Models/diabetes_model.sav'
- Heart Disease Prediction: Saved as 'Models/heart_disease_model.sav'
- Parkinson's Disease Prediction: Saved as 'Models/parkinsons_model.sav'

## Built With

- [Streamlit](https://streamlit.io) - A Python library for creating web applications for Machine Learning and Data Science.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please create an issue or make a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- The datasets used for training the models were sourced from reputable public repositories.
- Special thanks to the Streamlit community for providing a powerful and easy-to-use platform for deploying ML applications.





