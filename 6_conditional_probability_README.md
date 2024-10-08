## Conditional Probability

**Conditional Probability** is the likelihood of an event occurring given that another event has already occurred. It helps in understanding the relationship between two events and quantifies how the probability of one event is affected by the presence of another event.

### Definition

The conditional probability of event 'A' given that event 'B' has occurred is denoted as 'P(A | B)', and it is calculated using the formula:

'P(A | B) = P(A ∩ B) / P(B)'

Where:
- 'P(A | B)' is the **conditional probability** of event 'A' given event 'B'.
- 'P(A ∩ B)' is the **joint probability** that both events 'A' and 'B' occur.
- 'P(B)' is the **marginal probability** of event 'B'.

### Key Concepts

1. **Joint Probability (P(A ∩ B))**: This is the probability that both events 'A' and 'B' happen simultaneously. It is essential for calculating the conditional probability.

2. **Marginal Probability (P(B))**: This is the probability of event 'B' occurring without considering event 'A'. It acts as a normalization factor in the calculation of conditional probability.

### Understanding Conditional Probability

- **Interpretation**: Conditional probability quantifies how the occurrence of one event can change the likelihood of another event.
  
- **Example Scenario**: If we want to know the probability of a student passing an exam given that they attended all the classes, we use conditional probability to assess how class attendance influences passing.

### Practical Applications

- **Medical Testing**: To evaluate the probability of a patient having a disease given a positive test result, taking into account the prevalence of the disease and test accuracy.

- **Marketing**: Analyzing the probability of a customer purchasing a product given that they have viewed an advertisement.

- **Risk Assessment**: Estimating the likelihood of an event occurring (like an accident) given certain risk factors (like age or driving experience).

### Example

#### Scenario: Weather Prediction

Suppose we want to calculate the probability that it will rain (event 'A') given that it is cloudy (event 'B'). 

1. **Define the events**:
   - Let 'A' = It rains.
   - Let 'B' = It is cloudy.

2. **Given probabilities**:
   - P(A ∩ B) = 0.3 (Probability of rain and clouds)
   - P(B) = 0.6 (Probability of clouds)

3. **Calculate conditional probability**:
   - P(A | B) = P(A ∩ B) / P(B)
   - P(A | B) = 0.3 / 0.6 = 0.5

This means that if it is cloudy, there is a 50% chance of rain.

---

## Conclusion

Conditional probability is a crucial concept in probability theory that allows us to evaluate the likelihood of events in relation to one another. It is widely applicable in various fields, including statistics, finance, and machine learning.

---

## License

This project is open-source and available under the [MIT License](LICENSE).
