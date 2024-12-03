# Insurance Charges Prediction

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Workflow](#workflow)
- [Installation and Usage](#installation-and-usage)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This project simulates the role of a Data Scientist at a leading health insurance company. By analyzing customer data, we aim to build a machine learning model capable of predicting healthcare costs. Such insights can guide both the company and its customers in planning and optimizing healthcare services.

## Dataset

The analysis utilizes two datasets:
1. **`insurance.csv`** (training data): Contains details about healthcare customers and their billed medical costs.
2. **`validation_dataset.csv`** (testing data): Similar to the training dataset but excludes the `charges` column, used to test the predictive accuracy of the model.

### Dataset Details

| Column    | Data Type | Description                                                      |
|-----------|-----------|------------------------------------------------------------------|
| `age`       | int       | Age of the primary beneficiary.                                  |
| `sex`       | object    | Gender of the insurance contractor (male or female).             |
| `bmi`       | float     | Body mass index, a key indicator of body fat based on height and weight. |
| `children`  | int       | Number of dependents covered by the insurance plan.              |
| `smoker`    | object    | Indicates whether the beneficiary smokes (yes or no).            |
| `region`    | object    | The beneficiary's residential area in the US, divided into four regions. |
| `charges`   | float     | Individual medical costs billed by health insurance.             |

## Workflow

1. **Data Cleaning**: Preprocessing the data to handle missing values, encode categorical variables, and normalize numeric features.
2. **Exploratory Data Analysis (EDA)**: Gaining insights into the dataset through visualizations and summary statistics.
3. **Modeling**: Building and fine-tuning regression models to predict healthcare charges.
4. **Validation**: Testing the model's performance on unseen data (`validation_dataset.csv`).
5. **Interpretation**: Analyzing model outcomes and providing actionable insights.

## Installation and Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/insurance-charges-prediction.git
   cd insurance-charges-prediction
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebook to explore the project:
   ```bash
   jupyter notebook Insurance_Charges.ipynb
   ```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or feature requests.

## License

This project is licensed under the [MIT License](LICENSE).



