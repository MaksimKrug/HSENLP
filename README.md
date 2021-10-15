# HSENLP

## Data Sources
1) [Kaggle competition](https://www.kaggle.com/c/jigsaw-multilingual-toxic-comment-classification)
2) [GDrive](https://drive.google.com/file/d/1cjIH-BVLLAi_0qfx2E7DtJjl6G4opQla/view?usp=sharing)

We are using only toxic | not toxic labels (binary calssification)

## Repository Description
Classification.ipynb - man script with full code base <br>
requirements.txt - python venv reuirements <br>
runs - directory with tensorboard logs

## Results
|Model|Test Score|
|-----|----------|
|Word Freq|0.889|
|Logistic Regression|0.967|
|Random Forest|0.886|
|Linear Glove|0.949|
|Linear FastText|0.952|
|Linear Both|0.954|
|LSTM Glove|0.965|
|LSTM FastText|0.965|
|LSTM Both|0.971|