## Bayes' Theorem

**Bayes' Theorem** is a fundamental concept in probability theory that describes how to update the probability of a hypothesis based on new evidence. It provides a way to calculate the conditional probability of an event, given the prior knowledge of conditions related to the event.

### Formula

Bayes' Theorem is mathematically expressed as:

'P(H | E) = (P(E | H) * P(H)) / P(E)'

Where:
- 'P(H | E)' is the **posterior probability**: the probability of hypothesis 'H' given evidence 'E'.
- 'P(E | H)' is the **likelihood**: the probability of observing evidence 'E' given that hypothesis 'H' is true.
- 'P(H)' is the **prior probability**: the initial probability of hypothesis 'H' before observing the evidence.
- 'P(E)' is the **marginal probability**: the total probability of evidence 'E' under all hypotheses.

### Explanation of Terms

1. **Posterior Probability (P(H | E))**: This is what we want to find. It represents the updated probability of hypothesis 'H' after considering the new evidence 'E'.
  
2. **Likelihood (P(E | H))**: This is the probability of obtaining the evidence 'E' if hypothesis 'H' is true. It reflects how well the evidence supports the hypothesis.

3. **Prior Probability (P(H))**: This is our initial belief about the hypothesis before seeing the evidence. It represents our prior knowledge or assumption.

4. **Marginal Probability (P(E))**: This is the total probability of the evidence, considering all possible hypotheses. It acts as a normalizing constant to ensure that the probabilities sum to one.

### Practical Applications of Bayes' Theorem

- **Medical Diagnosis**: Used to determine the probability of a disease given the presence of specific symptoms and prior prevalence of the disease.
  
- **Spam Filtering**: Helps in classifying emails as spam or not spam based on the presence of certain keywords and their likelihood in each category.

- **Risk Assessment**: Employed in finance and insurance to evaluate risks based on prior incidents and new evidence.

### Example

#### Scenario: Medical Testing

Imagine a disease that affects 1% of a population. A test for the disease has a 90% true positive rate (sensitivity) and a 5% false positive rate. If a person tests positive, what is the probability they actually have the disease?

Using Bayes' Theorem:
- Let 'H' be the event that the person has the disease.
- Let 'E' be the event that the test result is positive.

1. **Prior Probability (P(H))** = 0.01 (1%)
2. **Likelihood (P(E | H))** = 0.90 (90%)
3. **P(E | not H)** = 0.05 (5% false positive rate) ⇒ P(not H) = 0.99 (99%)
4. **Marginal Probability (P(E))**:
   - P(E) = P(E | H) * P(H) + P(E | not H) * P(not H)
   - P(E) = (0.90 * 0.01) + (0.05 * 0.99) = 0.009 + 0.0495 = 0.0585

Now applying Bayes' Theorem:
- P(H | E) = (P(E | H) * P(H)) / P(E) = (0.90 * 0.01) / 0.0585 ≈ 0.1538 (15.38%)

This result shows that even with a positive test, there is only a 15.38% chance that the person actually has the disease, highlighting the importance of considering prior probabilities and the accuracy of tests.

---

## Conclusion

Bayes' Theorem is a powerful tool in statistics and probability, enabling us to update our beliefs based on new evidence. Its applications span various fields, making it an essential concept for data analysis and decision-making.

---

## License

This project is open-source and available under the [MIT License](LICENSE).
