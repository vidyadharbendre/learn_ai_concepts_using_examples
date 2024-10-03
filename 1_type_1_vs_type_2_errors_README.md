# Understanding Type 1 and Type 2 Errors in Hypothesis Testing

In hypothesis testing, **Type 1** and **Type 2** errors represent two kinds of mistakes we can make when drawing conclusions based on data. These errors occur when we incorrectly accept or reject the null hypothesis.

---

## What are Type 1 and Type 2 Errors?

### Type 1 Error (False Positive)
A **Type 1 error** occurs when we **reject the null hypothesis (H₀)** when it is actually **true**. In other words, it’s the error of finding a difference or effect when none exists.

- **Example**: A medical test incorrectly detects a disease in a healthy person.

### Type 2 Error (False Negative)
A **Type 2 error** occurs when we **fail to reject the null hypothesis (H₀)** when it is actually **false**. This error means concluding that there is no effect or difference when, in fact, there is.

- **Example**: A medical test fails to detect a disease in a sick person.

---

## Examples of Type 1 Errors

1. **Medical Diagnosis**:
   - **Scenario**: A test shows a patient has a disease when they are actually healthy.
   - **Null Hypothesis (H₀)**: The patient is healthy.
   - **Type 1 Error**: The test incorrectly diagnoses the patient with the disease.

2. **Scientific Research**:
   - **Scenario**: A study concludes a new drug is effective, but in reality, it has no effect.
   - **Null Hypothesis (H₀)**: The drug has no effect.
   - **Type 1 Error**: The study falsely finds a significant effect.

3. **Website A/B Testing**:
   - **Scenario**: A website A/B test shows that a new page design increases conversions, but in reality, it does not.
   - **Null Hypothesis (H₀)**: The new design has no impact on conversions.
   - **Type 1 Error**: The test incorrectly shows the new design is better.

---

## Examples of Type 2 Errors

1. **Medical Diagnosis**:
   - **Scenario**: A test fails to detect a disease in a patient who is actually sick.
   - **Null Hypothesis (H₀)**: The patient is healthy.
   - **Type 2 Error**: The test incorrectly concludes the patient does not have the disease.

2. **Scientific Research**:
   - **Scenario**: A study concludes that a new drug has no effect, but it actually does help the patients.
   - **Null Hypothesis (H₀)**: The drug has no effect.
   - **Type 2 Error**: The study fails to find the real effect of the drug.

3. **Jury Decision**:
   - **Scenario**: A guilty person is found innocent in a trial.
   - **Null Hypothesis (H₀)**: The defendant is innocent.
   - **Type 2 Error**: The jury fails to reject the null hypothesis, letting a guilty person go free.

---

## Summary of Errors

| Hypothesis Status  | Decision            | Result           |
|--------------------|---------------------|------------------|
| **Null is True**   | Reject Null          | **Type 1 Error** |
| **Null is True**   | Fail to Reject Null  | Correct Decision |
| **Null is False**  | Reject Null          | Correct Decision |
| **Null is False**  | Fail to Reject Null  | **Type 2 Error** |

---

## How to Reduce Errors

- **Reduce Type 1 Error**: Lower the significance level (**α**) of the test. For example, instead of setting α = 0.05, you can use α = 0.01.
- **Reduce Type 2 Error**: Increase the sample size or use more sensitive testing methods. Increasing the power of the test helps reduce Type 2 errors.

---

## License

This project is open-source and available under the [MIT License](LICENSE).

