# Predicting Student Retention: A Data-Driven Approach to Academic Success

## Project Overview
This project aims to analyze student data to identify key factors influencing academic performance and retention rates, specifically through logistic regression analysis. The project covers data preprocessing, descriptive analysis, logistic regression modeling, and findings interpretation.

## File Structure
- **Raw Data**: Original dataset with student academic and demographic information.
- **Categorical Descriptive**: Summary statistics for categorical variables like gender, commuter status, and seminar attendance.
- **Continuous Variable Descriptive**: Statistical summary for continuous variables (e.g., GPA, Units Enrolled, Age).
- **Logistic Regression Data**: Data preprocessed and formatted for logistic regression analysis.
- **LR_Results**: Results of the logistic regression analysis, including model coefficients and cut-off values.

## Data Analysis and Key Findings
### 1. Data Preprocessing
The dataset was cleaned by encoding categorical variables and scaling continuous variables to ensure compatibility with regression analysis.

### 2. Descriptive Statistics
#### Categorical Variables Summary:
This section includes summaries of GPA across age groups and other demographic variables. Key insights:
  | Age Group | Average GPA |
  |-----------|-------------|
  | 18-22     | 2.13        |
  | 23-27     | 2.35        |
  | 28-32     | 2.41        |

#### Continuous Variables Summary:
The statistical summary of continuous variables provided insights into data variability.
  - **Mean GPA**: 2.87
  - **Mean Units Enrolled**: 12.27
  - **Mean Age**: 21.7
  - Includes standard deviation and median values for better variance understanding.

### 3. Logistic Regression Analysis
The logistic regression model assessed the probability of a student dropping out based on:
- **Predictor Variables**: GPA, units enrolled, registration status, local vs. commuter status, and seminar attendance.
- **Coefficients** (sampled from **LR_Results**):
  | Variable                  | Coefficient (b) |
  |---------------------------|-----------------|
  | Intercept (b0)            | -0.106         |
  | GPA                       | -1.593         |
  | Units Enrolled            | 0.201          |
  | Full-Time Status          | 0.384          |
  | Local (vs. Commuter)      | 0.934          |
  | Seminar Not Attended      | -0.456         |

#### Key Findings:
- **GPA and Full-Time Status** negatively associate with dropout probability, suggesting students with higher GPAs or full-time enrollment are less likely to drop out.
- **Commuter Status** and **Seminar Attendance** also impact dropout likelihood, with local students and those attending seminars at lower risk.

### 4. Cut-Off Value for Prediction
A cut-off probability (e.g., 0.205) was used to classify students likely to drop out, balancing model precision and recall.

## Results and Interpretation
The model identified factors significantly affecting student retention, enabling targeted intervention strategies:
- **At-risk groups include**:
  - Commuter students
  - Students with lower GPAs
  - Students not attending academic seminars

## Conclusion
This analysis provides actionable insights for institutions to enhance student retention programs by focusing on identified critical factors.

---

This project demonstrates the use of logistic regression to model student retention, offering quantitative insights into academic success and student support strategies.
