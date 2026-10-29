# Human Activity Recognition Using Machine Learning

A machine learning classification project that predicts six human physical activities using smartphone accelerometer and gyroscope sensor data.

## Project Overview

This project explores how machine learning algorithms can recognize human activities from smartphone sensor measurements. It focuses on comparing different classification methods, evaluating their performance, and understanding their potential applications in human-computer interaction, wearable technology, and healthcare.

The project is being developed as part of an Applied Machine Learning course at Whitman College.

## Dataset

**Source:** UCI Machine Learning Repository

**Dataset:** Human Activity Recognition Using Smartphones

- Total observations: 10,299
- Features: 561 numerical features
- Participants: 30 volunteers
- Training observations: 7,352
- Testing observations: 2,947

[Access the original dataset](https://archive.ics.uci.edu/dataset/240/human+activity+recognition+using+smartphones)

## Classification Targets

The model will classify six physical activities:

1. Walking
2. Walking upstairs
3. Walking downstairs
4. Sitting
5. Standing
6. Lying down

## Machine Learning Algorithms

Four classification algorithms will be implemented and compared:

- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Random Forest
- Gaussian Naive Bayes

## Evaluation Metrics

Model performance will be evaluated using:

- Accuracy
- Precision
- Recall
- Macro F1-score
- Confusion matrices
- Computational efficiency

The original participant-separated training and testing sets will be preserved to reduce data leakage.

## Technologies

- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Streamlit (planned for the final demonstration)

## Project Status

**Phase 1: Proposal** - Completed

**Phase 2: Data Preprocessing and Model Development** - Upcoming

**Phase 3: Final Model Evaluation and Demonstration** - Planned

## Project Structure

```text
human-activity-recognition-ml/
├── README.md
├── docs/
├── data/
├── notebooks/
├── src/
├── models/
└── results/
```

## Future Applications

Human Activity Recognition has potential applications in:

- Wearable health monitoring
- Physical rehabilitation technology
- Fitness and activity tracking
- Assistive technologies
- Human-computer interaction

This project is an academic exploration of classification methods, not a clinically validated healthcare system.

## Author

Tigistu Korga  
Computer Science, Whitman College

## License

MIT License for original project code. The dataset remains subject to its original source terms.
