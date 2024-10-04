# ML Advanced Hyperparameter Tuning

This repository contains an advanced machine learning project focused on optimizing model performance through hyperparameter tuning. The goal of the project is to demonstrate how to fine-tune different machine learning models using various techniques to achieve better results.

## Table of Contents

- [Project Overview](#project-overview)
- [Hyperparameter Tuning Techniques](#hyperparameter-tuning-techniques)
- [Installation](#installation)
- [Usage](#usage)
- [Models and Hyperparameters](#models-and-hyperparameters)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The goal of this project is to demonstrate the importance of hyperparameter tuning in improving machine learning model performance. It showcases different strategies to adjust model parameters and optimize them to get the best possible outcome.

This project covers:

- Randomized Search
- Grid Search
- Bayesian Optimization
- Hyperopt
- Cross-validation for robust tuning

## Hyperparameter Tuning Techniques

The following hyperparameter tuning techniques are implemented in this project:

1. **Grid Search**: Exhaustive search over a specified parameter grid.
2. **Randomized Search**: Random sampling of hyperparameter space.
3. **Bayesian Optimization**: An optimization technique based on probabilistic models.
4. **Hyperopt**: An advanced optimization library used for hyperparameter tuning.

## Installation

To run this project, follow the steps below:

1. Clone the repository:
   ```bash
   git clone https://github.com/ansh-vyas/ML-adv-hyperparameter-tunning.git
   ```

2. Navigate to the project directory:
   ```bash
   cd ML-adv-hyperparameter-tunning
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

Once the environment is set up, you can start tuning the models. The key scripts included in this repository are:

- `grid_search.py`: Implements grid search for hyperparameter tuning.
- `random_search.py`: Implements randomized search for hyperparameter tuning.
- `bayesian_optimization.py`: Implements Bayesian optimization.
- `hyperopt_tuning.py`: Demonstrates the use of Hyperopt for advanced hyperparameter tuning.

To perform grid search, you can run:

```bash
python grid_search.py
```

Similarly, you can run other scripts for different tuning techniques.

## Models and Hyperparameters

The following models are used for hyperparameter tuning:

- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)
- XGBoost

For each model, the most important hyperparameters are fine-tuned, such as:

- **Logistic Regression**: `C`, `penalty`
- **Random Forest**: `n_estimators`, `max_depth`, `min_samples_split`, `min_samples_leaf`
- **SVM**: `C`, `gamma`, `kernel`
- **XGBoost**: `learning_rate`, `n_estimators`, `max_depth`, `min_child_weight`, `subsample`

## Results

The project compares the performance of models before and after tuning, highlighting the improvements achieved by adjusting the hyperparameters. The results show significant gains in accuracy, precision, and recall after proper tuning.

## Contributing

Contributions are welcome! If you have any suggestions, feel free to open an issue or submit a pull request. To contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m 'Add a new feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature-branch
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
