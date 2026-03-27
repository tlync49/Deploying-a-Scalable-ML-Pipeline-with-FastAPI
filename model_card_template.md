# Model Card

For additional information see the Model Card paper: https://arxiv.org/pdf/1810.03993.pdf

## Model Details
Random Forest Classifier model using default hypterparameters from sklearn version 1.5.1.

## Intended Use
Classifying incomes above and below $50,000 based on employment and demographic data.

## Training Data
Training data is compiled from the Census Income dataset. It was extracted by Barry Becker from the 1994 Census database: https://archive.ics.uci.edu/dataset/20/census+income

## Evaluation Data
The test data is about 20% of the census.csv file. 

## Metrics
Model evaluated precision (0.7353), recall (0.6378) and F1 (0.6831)

Metrics for specific slices can be viewed with slice_output.txt.

## Ethical Considerations
The dataset is from 1994; likely reflecting societal bias and context in that time frame.

## Caveats and Recommendations
This model is for educational use only. 