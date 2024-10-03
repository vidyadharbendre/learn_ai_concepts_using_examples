# Understanding Hypothesis Testing in Statistics

Hypothesis testing is a statistical method used to make inferences or draw conclusions about a population based on sample data. It helps determine whether a certain claim (hypothesis) about a dataset is supported by the evidence provided by the sample.

---

## What is Hypothesis Testing?

In hypothesis testing, we begin with two hypotheses:

- **Null Hypothesis (H₀)**: A statement of no effect, no difference, or no relationship. It is what we seek to disprove.
- **Alternative Hypothesis (H₁ or Ha)**: A statement that contradicts the null hypothesis, representing an effect, difference, or relationship.

The goal is to use sample data to decide whether to reject the null hypothesis in favor of the alternative hypothesis, or fail to reject the null hypothesis.

---

## Steps in Hypothesis Testing

1. **State the Hypotheses**:
   - Null Hypothesis (H₀) and Alternative Hypothesis (H₁).

2. **Set the Significance Level (α)**:
   - This is the probability threshold (commonly 0.05 or 5%) at which we will reject the null hypothesis.

3. **Collect the Data**:
   - Gather the sample data relevant to the hypothesis being tested.

4. **Calculate the Test Statistic**:
   - Use appropriate statistical tests (e.g., z-test, t-test) to calculate a test statistic based on the data.

5. **Make a Decision**:
   - Compare the test statistic with a critical value or p-value to decide whether to reject or fail to reject the null hypothesis.

---

## Example 1: Medical Drug Testing

**Scenario**: A pharmaceutical company wants to test if a new drug is more effective than the current standard treatment.

- **Null Hypothesis (H₀)**: The new drug is no more effective than the current treatment.
- **Alternative Hypothesis (H₁)**: The new drug is more effective than the current treatment.

1. Set the significance level at **α = 0.05**.
2. The company runs clinical trials with two groups (one for the new drug, one for the current treatment) and collects the data.
3. The test statistic (e.g., t-test) is calculated, and the p-value is compared to **α**.
4. If the p-value < 0.05, the company rejects the null hypothesis, concluding that the new drug is more effective. Otherwise, they fail to reject the null hypothesis.

---

## Example 2: Website A/B Testing

**Scenario**: A company wants to test whether a new version of their website increases user engagement (measured by clicks) compared to the current version.

- **Null Hypothesis (H₀)**: The new website version has the same engagement as the current version.
- **Alternative Hypothesis (H₁)**: The new website version has higher engagement than the current version.

1. Set the significance level at **α = 0.05**.
2. Data is collected from users exposed to both the new and current versions of the website.
3. A statistical test (e.g., z-test) is used to compare the engagement between the two versions.
4. If the p-value < 0.05, the company rejects the null hypothesis, concluding that the new version increases engagement. Otherwise, they fail to reject the null hypothesis.

---

## Example 3: Manufacturing Quality Control

**Scenario**: A factory manager wants to check if a new machine produces fewer defective items than the current machine.

- **Null Hypothesis (H₀)**: The new machine produces the same or more defective items compared to the current machine.
- **Alternative Hypothesis (H₁)**: The new machine produces fewer defective items than the current machine.

1. Set the significance level at **α = 0.05**.
2. The manager collects sample data on the number of defective items produced by both machines.
3. A statistical test (e.g., chi-square test) is applied to compare the number of defects.
4. If the p-value < 0.05, the null hypothesis is rejected, concluding that the new machine produces fewer defects. Otherwise, the null hypothesis is not rejected.

---

## Summary of Hypothesis Testing

| Component                  | Description                                                                 |
|----------------------------|-----------------------------------------------------------------------------|
| **Null Hypothesis (H₀)**    | Assumes no effect or difference; what we aim to disprove.                   |
| **Alternative Hypothesis (H₁)** | Assumes an effect or difference exists.                                   |
| **Significance Level (α)**  | The threshold for rejecting H₀, commonly 0.05.                             |
| **Test Statistic**          | A value calculated from sample data, used to compare with critical values.  |
| **p-value**                 | The probability of observing the data if H₀ is true. If p-value < α, reject H₀. |
| **Conclusion**              | Either reject H₀ (supporting H₁) or fail to reject H₀.                     |

---

## Types of Hypothesis Tests

### Common tests include:

- **Z-Test**: Used for large sample sizes and known population variance.
- **T-Test**: Used for small sample sizes or unknown population variance.
- **Chi-Square Test**: Used for categorical data and testing relationships between variables.

---

## How to Interpret Results

- **Reject H₀**: There is enough evidence to support the alternative hypothesis (**H₁**).
- **Fail to Reject H₀**: There is not enough evidence to support the alternative hypothesis, but this does not mean H₀ is true—just that the data does not provide strong enough evidence to reject it.

---

## License

This project is open-source and available under the [MIT License](LICENSE).
