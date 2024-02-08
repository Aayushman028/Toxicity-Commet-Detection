# Toxicity-Commet-Detection

## About The Project
<p align="center">
  <img width="621" alt="logo" src="https://i.pinimg.com/736x/34/86/08/3486082dc4d6369663a19728cffaa63f.jpg">
</p>

This project focuses on developing a toxicity comment detection model based on various parameters. Leveraging TensorFlow, Pandas, Matplotlib, and Scikit-learn, a robust system capable of identifying toxic behavior in online comments has been created.

## Dataset

You can downloaded the dataset from [kaggle](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge). Use the underlying download link to download the dataset.

### Instructions

* Navigate to `data` section
* In the `Data Explorer`, you will find four separate zip archives to download
* Download `test.csv.zip`, `test_labels.csv.zip` and `train.csv.zip`
* Extract the files
* Copy the CSV files to the `data` directory

The following list enumerates different classes (types) of comments -

| Toxic | Very Toxic | Obscene | Threat | Insult | Hate | Neutral |
|-------|------------|---------|--------|--------|------|---------|


## Tools and Technologies:

* TensorFlow: Utilized for building and training deep learning models for toxicity detection, specifically employing Long Short-Term Memory (LSTM) networks.
* Pandas: Employed for data manipulation and analysis.
* Matplotlib: Utilized for data visualization and analysis.
* Scikit-learn: Used for machine learning algorithms and evaluation metrics.

### Key Features:
* Preprocessing: The dataset was cleaned and prepared for modeling.
* Model: LSTM networks were used for classification, with 4 epochs during training.
* Evaluation: The accuracy achieved was 0.480.

## Future Improvements:

* Enhance model performance to increase accuracy.
* Expand dataset diversity by incorporating data from Twitter and other social media platforms.
* Increase data evaluation by collecting more labeled samples for training.

## License

Distributed under the MIT License. See [LICENSE](https://github.com/ShaanCoding/ReadME-Generator/blob/main/LICENSE.md) for more information.

## Authors

