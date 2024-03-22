
# Movie Recommender Using K-Nearest Neighbors

This project demonstrates the application of the K-Nearest Neighbors (K-NN) algorithm to recommend movies similar to a given movie, in this case, 'The Post'. The approach involves feature scaling and model fitting with movie data.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What you need to install the software and how to install them:

```bash
# Example
pip install pandas scikit-learn matplotlib seaborn
```

### Installing

A step-by-step series of examples that tell you how to get a development environment running:

1. Clone the repo:
```bash
git clone <this_repo_url>
```

2. Install the required packages:
```bash
pip install -r requirements.txt
```

## Usage

1. **Data Preparation**: The data for the movies is prepared and visualized to understand the distribution of various features.

2. **Feature Set Definition**: Features are defined for the K-NN model.

3. **Feature Scaling**: Input features for the model are scaled for optimal performance.

4. **Model Training**: The K-NN model is trained with the scaled features.

5. **Prediction**: The model predicts the 5 most similar movies to 'The Post'.

## Built With

- [Pandas](https://pandas.pydata.org/) - For data manipulation and analysis.
- [Scikit-Learn](https://scikit-learn.org/stable/) - For machine learning model implementation.
- [Matplotlib](https://matplotlib.org/) & [Seaborn](https://seaborn.pydata.org/) - For data visualization.

## Authors

- **Andrew Morris** - *Initial work*
