# Software Developer Salary Prediction App

This project is a Streamlit web application that predicts software developer salaries based on data from the Stack Overflow Developer Survey 2024. The app allows users to explore salary data and predict salaries based on user input.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Model](#model)
- [Contributing](#contributing)
- [Credits](#credits)
- [License](#license)

## Overview

The Software Developer Salary Prediction App is designed to help users understand and predict software developer salaries based on various factors such as country, education level, and years of experience. The app provides an interactive interface for exploring salary data and making predictions.

## Features

- **Explore Page**: Visualize salary data based on country and experience.
- **Predict Page**: Predict software developer salaries based on user input.
- **Interactive Charts**: Pie charts and bar charts for data visualization.

## Installation

To run the app locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/dev_salary_prediction_app.git
    cd dev_salary_prediction_app
    ```

2. **Create and activate a virtual environment**:
    ```bash
    python3 -m venv .venv
    source .venv/bin/activate
    ```

3. **Install the required dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Streamlit app**:
    ```bash
    streamlit run app.py
    ```

## Usage

Once the app is running, you can access it in your web browser at `http://localhost:8501`. The app has two main pages:

- **Explore Page**: Provides visualizations of the salary data.
- **Predict Page**: Allows users to input their details and get a salary prediction.

## Data

The data used in this project is from the Stack Overflow Developer Survey 2024. The dataset includes information about developers' countries, education levels, years of experience, and salaries.

## Model

The salary prediction model is a machine learning model trained on the survey data. The model uses features such as country, education level, and years of experience to predict salaries. The model and preprocessing steps are saved in a `saved_steps.pkl` file, which is loaded by the app.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please create a pull request or open an issue.

1. **Fork the repository**.
2. **Create a new branch**:
    ```bash
    git checkout -b feature-branch
    ```
3. **Make your changes**.
4. **Commit your changes**:
    ```bash
    git commit -m "Add some feature"
    ```
5. **Push to the branch**:
    ```bash
    git push origin feature-branch
    ```
6. **Create a pull request**.

## Credits

This project was created with the help of a tutorial by Patrick Loeber. You can find the tutorial here: https://www.youtube.com/watch?v=xl0N7tHiwlw.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
