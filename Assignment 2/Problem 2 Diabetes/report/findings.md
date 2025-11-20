# Diabetes Dataset Findings Report

## A) Random Sample Glucose Analysis

Sample Statistics:
- Sample Size: 25 observations
- Sample Mean Glucose: 115.60 mg/dL
- Sample Max Glucose: 181 mg/dL

Population Statistics:
- Population Size: 768 observations
- Population Mean Glucose: 120.89 mg/dL
- Population Max Glucose: 199 mg/dL

Key Findings:
- The sample mean glucose (115.60) is slightly lower than the population mean (120.89), with a difference of 5.29 mg/dL
- The sample maximum glucose (181) is also lower than the population maximum (199), with a difference of 18 mg/dL
- The sample distribution closely mirrors the population distribution, indicating good representativeness despite the small sample size
- Both distributions show similar spread and shape, which validates the random sampling approach

## B) 98th Percentile BMI Comparison

Sample Statistics:
- 98th Percentile BMI: 43.77
- Mean BMI: 30.10
- Median BMI: 29.70

Population Statistics:
- 98th Percentile BMI: 47.53
- Mean BMI: 31.99
- Median BMI: 32.00

Key Findings:
- The sample 98th percentile BMI (43.77) is lower than the population value (47.53), with a difference of 3.76
- The sample mean BMI (30.10) is also slightly lower than the population mean (31.99), differing by 1.89
- The sample median BMI (29.70) shows a difference of 2.30 from the population median (32.00)
- The smaller sample size (n=25) does not fully capture the extreme values present in the population, which explains the lower 98th percentile

## Part C: Bootstrap Analysis of Blood Pressure

Bootstrap Parameters:
- Number of bootstrap samples: 500
- Sample size per bootstrap: 150 observations with replacement

Bootstrap Statistics:
- Average Mean Blood Pressure: 69.11 mg/dL
- Average Standard Deviation: 19.09
- Average 98th Percentile: 107.82

Population Statistics:
- Population Mean: 69.11 mg/dL
- Population Standard Deviation: 19.36
- Population 98th Percentile: 108.00

Key Findings:
- The bootstrap average mean (69.11) matches the population mean exactly
- The bootstrap average standard deviation (19.09) is very close to the population value (19.36)
- The bootstrap 98th percentile (107.82) closely approximates the population value (108.00)
- The convergence plots show that the bootstrap estimates stabilize quickly
- Bootstrap distributions are normally distributed around the population parameters

## Overall Conclusions

1. Random Sampling: A sample of 25 observations provides reasonable estimates but could underestimate extreme values
2. Percentile Analysis: The 98th percentile is sensitive to sample size as larger samples better capture extreme values
3. Bootstrap Method: Bootstrap sampling with 500 iterations of 150 observations each gives highly accurate estimates of population parameters