# Statistics-Parametric-and-Non-Parametric-Tests-in-Data-Science
**Statistics** is one of the most basic disciplines in data science. It provides the mathematical basis for *collecting, organizing, analyzing, interpreting, and presenting data in a meaningful way.* Without statistics, it would be hard to identify trends, test the reliability of data, make predictions, and draw valid conclusions from large data sets. Data scientists use statistical methods to turn raw data into actionable insights. These insights can inform decisions in fields like healthcare, finance, marketing, education, and technology.

Statistics is broadly divided into **descriptive statistics and inferential statistics**

![Image description](https://dev-to-uploads.s3.us-east-2.amazonaws.com/uploads/articles/qg3yzodbns9h4fhcpgui.jpg)

Descriptive statistics summarize and describe the characteristics of a dataset using measures such as the *mean, median, mode, range, variance, and standard deviation.* These measures help understand the central tendency and spread of data. Inferential statistics, on the other hand, *use sample data to make predictions or draw conclusions about a larger population.* Techniques such as hypothesis testing, confidence intervals, and regression analysis fall under inferential statistics and are essential for making data-driven decisions.

One of the most important applications of inferential statistics is hypothesis testing, which helps determine whether observed differences or relationships in data are statistically significant or simply occurred by chance. Hypothesis testing generally involves two competing statements:

- Null Hypothesis (H₀): Assumes there is no significant difference or relationship.
- Alternative Hypothesis (H₁): Assumes a significant difference or relationship exists.

To evaluate these hypotheses, statisticians use parametric or non-parametric tests, depending on the nature of the data.


![Image description](https://dev-to-uploads.s3.us-east-2.amazonaws.com/uploads/articles/7ivn5wves2kqlr5xw50t.webp)

## Parametric Tests

Parametric tests are statistical methods that assume data follows a normal distribution and meets conditions such as equal *variances and independent observations.* They are generally more powerful and accurate when these assumptions are satisfied.

## Common Parametric Tests
- Independent Samples t-Test: Compares the means of two independent groups.
- Paired Samples t-Test: Compares two related measurements from the same group.
- ANOVA (Analysis of Variance): Compares the means of three or more groups.
- Pearson Correlation: Measures the strength and direction of a linear relationship between two continuous variables.

**Advantages**

- High statistical power.
- Accurate when assumptions are met.
- Suitable for continuous numerical data.

**Non-Parametric Tests**

Non-parametric tests do not require data to follow a normal distribution. They are ideal for ordinal, ranked, or skewed data and are more robust when statistical assumptions are not met.

**Common Non-Parametric Tests**

![Image description](https://dev-to-uploads.s3.us-east-2.amazonaws.com/uploads/articles/qtq8gydjs3srb9i2au6i.webp)

- *Mann–Whitney U Test*: Alternative to the independent t-test.
- *Wilcoxon Signed-Rank Test*: Alternative to the paired t-test.
- *Kruskal–Wallis Test*: Alternative to ANOVA.
- *Spearman Rank Correlation*: Measures relationships between ranked variables.

**Advantages**

- No normality assumption required.
- Works well with small samples and outliers.
- Suitable for ordinal and non-normal data.

**Conclusion**

Choosing between parametric and non-parametric tests depends on the characteristics of the data. Parametric tests are preferred when data meets statistical assumptions, while non-parametric tests provide reliable alternatives when those assumptions are violated. Both are essential tools for making accurate, evidence-based decisions in data science.
