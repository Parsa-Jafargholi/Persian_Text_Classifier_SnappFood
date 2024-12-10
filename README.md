
# Persian Text Classification

This project focuses on preprocessing and classifying Persian textual data using machine learning and deep learning models.

## Features
1. **Data Preprocessing**:
   - Cleaning text, removing punctuation, and stop words.
   - Tokenization and normalization using `hazm` and `finglish`.
2. **Data Visualization**:
   - Analyzing and visualizing features such as word counts per sentence.
3. **Modeling**:
   - Random Forest with hyperparameter tuning using K-fold cross-validation.
   - Multinomial Naïve Bayes for efficient text classification.
   - RNN (LSTM) with embedding layers for sequence learning.

## Prerequisites
- Python 3.8+
- Libraries:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `sklearn`
  - `hazm`
  - `tensorflow`

## Installation
Install the required libraries using:
```bash
pip install numpy pandas matplotlib scikit-learn hazm tensorflow
```

## Data Description
- **train.csv**: Training dataset with comments and their labels.
- **dev.csv**: Development dataset for validation.
- **test.csv**: Test dataset for evaluation.
- **kharazi_stopwords.txt**: Persian stop words used for text cleaning.

## How to Run
1. Clone the repository.
2. Place the datasets (`train.csv`, `dev.csv`, `test.csv`, and `kharazi_stopwords.txt`) in the project directory.
3. Run the Jupyter Notebook to preprocess data, visualize features, and train models.

## Project Structure
- **`DataMining_Project(Task1).ipynb`**: Main notebook for preprocessing, visualization, and modeling.
- **`train.csv`**, **`dev.csv`**, **`test.csv`**: Datasets.
- **`kharazi_stopwords.txt`**: Stop words file.

## Future Improvements
- Fine-tune hyperparameters of the RNN model for better results.
- Use larger datasets for training and evaluation.

## Acknowledgments
- `hazm` and `finglish` libraries for Persian text preprocessing.
- `scikit-learn` for machine learning models.
- `tensorflow` for deep learning models.
