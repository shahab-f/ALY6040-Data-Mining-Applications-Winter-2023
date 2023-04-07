### Signature Assignment - EDA
### ABSTRACT
The purpose of this study is to conduct data preprocessing and Exploratory Data Analysis (EDA) on two datasets - application_record and credit_record. To achieve this, the study starts by loading various libraries such as dplyr, tidyr, magrittr, kableExtra, ggplot2, GGally, and psych.

The first step involves displaying the structure of both datasets and checking their data completeness, accuracy, and validity. The study looks for duplicate values in both datasets and checks for missing values using the sum() function. Accuracy checks are conducted by summarizing the credit_record, while for application_record, a table is generated using summarytools and formatted using kable_classic().

To eliminate unrealistic values in application_record, rows with values outside the specified range are deleted. The study then converts DAYS_BIRTH to AGE and DAYS_EMPLOYED to YEARS_EMPLOYED by dividing by -365.25. Positive values in the YEARS_EMPLOYED variable are replaced with zero to indicate unemployment.

EDA is conducted to identify outliers in the dataset. A boxplot matrix of outlier-prone numeric variables in the application_record dataset is displayed. The dataset is then converted to a matrix, and boxplots are plotted for each pair or single variable. The YEARS_EMPLOYED variable is slightly modified by replacing 0 values with 0.1, and logarithmic transformation is applied to both YEARS_EMPLOYED and AMT_INCOME_TOTAL variables to improve their distribution.

The study then merges the two datasets, creating a cross-tabulation table and generating a bar plot of credit status by gender. A random sample of 100 points is created to produce a scatterplot matrix of numerical variables in the credit application dataset.

Finally, a Chi-square test is conducted to reveal the relationship between credit status and categorical variables in the dataset. Overall, these preprocessing and EDA steps produce a clean and well-structured dataset, which is essential for accurate data analysis and modeling.

[Link to my HTML report](https://shahab-f.github.io/ALY6040_-M3_-signature-assignment-EDA_-FeghahatiS---rev-7.html)
