# Fueling the Fire: Analysis of Emotional Language in Social Media

A computational social science project analyzing the influence of various predictors on emotional expressions (particularly anger) in social media discourse.


## Project Overview

This project investigates how different factors influence the prevalence and intensity of emotional language in online discussions, with a focus on anger and related emotions.

This project is part of the course "Foundations of computational social systems" at the TU Graz, conducted in the winter semester of 2025.

### Authors
Moritz Horsch, Moritz Koch, Vincent Jakl

## Data

As our dataset, the one-milion-corpus dataset was used, available to download at https://ofai.github.io/million-post-corpus/.

- **Source**: Social media corpus stored in `dataset/corpus.sqlite3`
- **Preprocessed Data**: 
  - `dataset/descriptive_stats.csv` - Descriptive statistics
  - `dataset/test_stats.csv` - Statistical test results
  - `dataset/bootstrap_stats.csv` - Bootstrap analysis results

## Analysis Pipeline

For the emotion analysis in `code/preprocessing.ipynb`, we used the pretrained model `/visegradmedia-emotion/Emotion_RoBERTa_german6_v7` from Hugging Face.

1. **Preprocessing** (`code/preprocessing.ipynb`) - Data cleaning and preparation
2. **Exploration** (`code/exploration.ipynb`) - Initial data exploration
3. **Data Analysis** (`code/data_analysis.ipynb`) - Statistical analyses and hypothesis testing
4. **Visualization** (`code/tables_and_plots.ipynb`) - Generation of figures and tables for publication

## Key Outputs

- Statistical test results with significance labels
- Effect size visualizations
- Emotion distribution analyses
- Comparative plots across different predictors and criteria

## Project Structure
├── code/ # Analysis notebooks and scripts\
└── dataset/ # Data files and results