# CS4622-Lab_1
Machine Learning Lab 1
## Data-set Description

1. For this lab, 2 CSV files have been provided.
  - train.csv : Training data set with 28,520 rows and columns with 256 features and 4 target labels
  - valid.csv : Validation data set with 750 rows and columns with 256 features and 4 target labels
2. Both CSV files are generated using the dataset AudioMNIST.
3. The first 256 columns are 256 values of the speaker embedding vector of each audio file in the data set AudioMNIST created using wav2vec-base. The last 4 columns are speaker-related label corresponding to each speaker embedding vector.
  - Label 1 - Speaker ID
  - Label 2 - Speaker age
  - Label 3 - Speaker gender
  - Label 4 - Speaker accent

## Assignment Tasks

Task is to apply all that you learned about feature selection & engineering for each target
label.

1. Feature selection/removal: Eg. using data cleaning/feature scoring techniques (SHAP values)
2. Feature engineering
3. Feature crossing
1
4. Any other advanced feature engineering techniques
5. Dimensionality Reduction
6. Etc. . .

Finally,  should give the reduced set of features enough to predict each target label.
