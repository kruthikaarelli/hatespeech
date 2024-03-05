# Hate Speech Recognition

## Description

This project implements a hate speech recognition system using machine learning techniques. It aims to classify text data into categories such as hate speech, offensive language, or neither. The classification is based on features extracted from text using TF-IDF vectorization and is performed using a Linear Support Vector Classifier (SVM).

## Packages Used

- pandas: For data manipulation and analysis.
- re: For regular expressions used in text preprocessing.
- nltk: For natural language processing tasks such as tokenization.
- seaborn: For creating visualizations such as count plots and heatmaps.
- sklearn: For machine learning algorithms and tools.

## Plots

- Count plot: Visualizes the distribution of classes based on the 'hate_speech' attribute.
- Heatmap: Visualizes the correlation between numerical attributes in the dataset.

## Machine Learning Algorithm

- Linear Support Vector Classifier (SVM): Used for text classification based on TF-IDF features extracted from the text data.

## Project Structure

- `hate_speech_recognition.py`: Main script containing the implementation.
- `labeled_data.csv`: Dataset containing labeled text data.

