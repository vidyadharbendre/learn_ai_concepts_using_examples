# Precision and Recall

**Precision** and **Recall** are two essential metrics in evaluating the performance of a classification model, especially in scenarios with imbalanced datasets. These metrics are used to measure the relevance of a model’s predictions.

---

## What is Precision?

**Precision** measures how many of the positive predictions made by the model are actually correct. It gives the proportion of true positives (correctly predicted positive instances) out of all positive predictions (both correct and incorrect).

**Precision Formula**:
`'Precision = (True Positives) / (True Positives + False Positives)'`

### Key Points:
- **True Positives (TP)**: Instances where the model correctly predicted the positive class.
- **False Positives (FP)**: Instances where the model incorrectly predicted the positive class (false alarms).

---

## What is Recall?

**Recall**, also known as **Sensitivity** or **True Positive Rate**, measures how many actual positive instances the model was able to identify correctly. It gives the proportion of true positives out of all actual positive instances.

**Recall Formula**:
`'Recall = (True Positives) / (True Positives + False Negatives)'`

### Key Points:
- **False Negatives (FN)**: Instances where the model failed to predict the positive class (missed predictions).

---

## Precision vs. Recall

| Metric     | Precision                                      | Recall                                         |
|------------|------------------------------------------------|------------------------------------------------|
| **Goal**   | Measures accuracy of positive predictions      | Measures coverage of actual positives          |
| **Focus**  | How many selected items are relevant?           | How many relevant items are selected?          |
| **Trade-off** | High precision leads to fewer false positives, but may result in more false negatives | High recall leads to fewer false negatives, but may result in more false positives |
| **Use Cases** | Important when false positives are costly (e.g., spam detection) | Important when false negatives are costly (e.g., disease detection) |

---

## The Precision-Recall Trade-off

- **High Precision, Low Recall**: The model is very accurate in its positive predictions but may miss many actual positive cases.
- **High Recall, Low Precision**: The model captures most positive cases but also makes many incorrect positive predictions.
- **Balanced**: Ideally, a model should aim for a balance between precision and recall, depending on the problem at hand.

### F1 Score

The **F1 Score** is the harmonic mean of precision and recall. It provides a single metric to balance the two.

**F1 Score Formula**:
`'F1 Score = 2 * (Precision * Recall) / (Precision + Recall)'`

The F1 score ranges between 0 and 1, where a score closer to 1 indicates better precision-recall balance.

---

## Why Precision and Recall are Important?

1. **Imbalanced Datasets**: Precision and recall are crucial for evaluating models on imbalanced datasets, where accuracy can be misleading.
2. **Model Tuning**: By understanding precision and recall, you can adjust your model to improve performance in either minimizing false positives or false negatives.
3. **Real-world Scenarios**: Many real-world problems, such as medical diagnosis, fraud detection, and spam filtering, rely on precision and recall to avoid harmful outcomes.

---

## Practical Applications

- **Spam Detection**: In email classification, you want high precision (avoiding false positives, i.e., legitimate emails marked as spam).
- **Medical Diagnosis**: In disease detection, recall is often more important to minimize false negatives (i.e., missed diagnoses).
- **Fraud Detection**: A high recall model can help detect more fraudulent transactions, but precision needs to be balanced to avoid too many false alarms.

---

## Conclusion

Precision and recall are key metrics in assessing classification models, especially when dealing with imbalanced datasets. While precision ensures that positive predictions are accurate, recall ensures that all actual positives are captured. Understanding the trade-off between these metrics helps in model tuning and decision-making based on the problem context.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
