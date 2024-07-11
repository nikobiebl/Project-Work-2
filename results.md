# Table with Results (random_state=42)

| Classifier | Vectorizer | Accuracy | F1-Score | Precision | Recall | Processing Time (in min) |
|------------|------------|----------|----------|-----------|--------|-----------------|
| Dummy | TF-IDF | 0.497 | 0.495 | 0.496 | 0.495 | 0.01 |
| Random Forest | TF-IDF | 0.99 | 0.99 | 0.993 | 0.987 | 2.57 |
| Logistic Regression | TF-IDF | 0.989 | 0.989 | 0.985 | 0.992 | 0.02 |
| Linear Support Vector Machine | TF-IDF | 0.993 | 0.993 | 0.993 | 0.994 | 17.86 |
| Poly Support Vektor Machine | TF-IDF | 0.979 | 0.979 | 0.998 | 0.961 | 128.6 |
| Multinomial Naive Bayes | TF-IDF | 0.978 | 0.977 | 0.995 | 0.961 | 0.01 |
| K-Nearest-Neighbor | TF-IDF | 0.695 | 0.766 | 0.620 | 1.0 | 0.68 |
| Gradient Boosting Machine | TF-IDF | 0.943 | 0.944 | 0.93 | 0.959 | 3.45 |

## Multi Layer Perceptron Results by Time

| Classifier | Vectorizer | Accuracy | F1-Score | Precision | Recall | Processing Time |
|------------|------------|----------|----------|-----------|--------|-----------------|
| Multi Layer Perceptron | TF-IDF | 0.98413 | 0.98409 | 0.98440 | 0.98378 | 1m 0.5s |
| Multi Layer Perceptron | TF-IDF | 0.99497 | 0.99495 | 0.99578 | 0.99412 | 5m 0.4s |
| Multi Layer Perceptron | TF-IDF | 0.99592 | 0.99591 | 0.99566 | 0.99617 | 30m 0.6s |
| Multi Layer Perceptron | TF-IDF | 0.99605 | 0.99604 | 0.99564 | 0.99642 | 60m 0.8s |
| Multi Layer Perceptron | TF-IDF | 0.99516 | 0.99515 | 0.99451 | 0.99578 | 450m 56.3s |

## Multi Layer Perceptron Results by Iterations

| Classifier | Vectorizer | Accuracy | F1-Score | Precision | Recall | Iterations | Processing Time |
|------------|------------|----------|----------|-----------|--------|------------|-----------------|
| Multi Layer Perceptron | TF-IDF | 0.99318 | 0.99317 | 0.99247 | 0.99387 | 1 | 3m 8.0s |
