# Mushroom Classification using ID3 Decision Tree

A machine learning project implementing the ID3 (Iterative Dichotomiser 3) algorithm from scratch to classify mushrooms as edible or poisonous.

## Project Overview

This project was developed during my second year of college as part of my AI/ML coursework. It demonstrates the implementation of decision tree algorithms and compares custom implementation with scikit-learn's built-in classifier.

## Features

- **Custom ID3 Implementation**: Built from scratch using entropy and information gain
- **Data Preprocessing**: Label encoding for categorical features
- **Model Comparison**: Custom ID3 vs scikit-learn DecisionTreeClassifier
- **Pruning Techniques**: Depth-limited trees to prevent overfitting
- **Comprehensive Evaluation**: Classification reports with precision, recall, and F1-score

## Dataset

The project uses the mushroom dataset (`mushrooms.csv`) containing various mushroom characteristics to predict edibility.

**Data Split:**
- Training: 70% (5,686 samples)
- Validation: 10% (812 samples) 
- Testing: 20% (1,626 samples)

## Implementation Details

### ID3 Algorithm Components

1. **Entropy Calculation**: Measures information content
2. **Information Gain**: Determines best feature splits
3. **Tree Construction**: Recursive building with stopping criteria
4. **Pruning**: Max depth limitation for generalization

### Models Implemented

1. **ID3 without Pruning**: Full tree construction
2. **ID3 with Pruning**: Optimized depth using validation set
3. **Scikit-learn Baseline**: For performance comparison

## Results

All models achieved excellent performance:

- **ID3 (No Pruning)**: 100% accuracy
- **ID3 (With Pruning)**: 97.5% accuracy
- **Scikit-learn**: 100% accuracy

## Files

- `mushroom_classification.ipynb`: Main notebook with implementation
- `mushrooms.csv`: Dataset file
- `README.md`: Project documentation

## Requirements

```python
pandas
numpy
scikit-learn
```

## Usage

1. Ensure `mushrooms.csv` is in the project directory
2. Run the Jupyter notebook cells sequentially
3. View model comparisons and classification reports

## Key Learning Outcomes

- Understanding of decision tree algorithms
- Implementation of entropy and information gain
- Model evaluation and comparison techniques
- Overfitting prevention through pruning

---
*College Project - Second Year AI/ML Course*
