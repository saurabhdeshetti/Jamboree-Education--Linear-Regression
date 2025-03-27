# Jamboree Education - Linear Regression


## About Data
Jamboree is a renowned educational institution that has successfully assisted numerous students in gaining admission to top colleges abroad. With their proven problem-solving methods, they have helped students achieve exceptional scores on exams like GMAT, GRE, and SAT with minimal effort.
To further support students, Jamboree has recently introduced a new feature on their website. This feature enables students to assess their probability of admission to Ivy League colleges, considering the unique perspective of Indian applicants.
By conducting a thorough analysis, we can assist Jamboree in understanding the crucial factors impacting graduate admissions and their interrelationships. Additionally, we can provide predictive insights to determine an individual's admission chances based on various variables.

## Objective
As a data scientist/ML engineer hired by Jamboree, your primary objective is toanalyze the given dataset and derive valuable insights from it. Additionally, utilize the dataset to construct a predictive model capable of estimating an applicant's likelihood of admission based on the available features.

Solving this business case holds immense importance for aspiring data scientists and ML engineers.

Building predictive models using machine learning is widely popular among the data scientists/ML engineers. By working through this case study, individuals gain hands-on experience and practical skills in the field.

Additionally, it will enhance one's ability to communicate with the stakeholders involved in data-related projects and help the organization take better, data-driven decisions.

## Jamboree Education Data: Cleaning, Analysis and Visualization
Data Analysis and Visualization on Jamboree Education Data to provide insights and recommendations to improve their userbase.

<table>
  <tr>
    <th style="width:15%">Column</th>
    <th style="width:85%">Description</th>
  </tr>
  <tr>
    <td>Serial No. (Unique row ID)</td>
    <td>This column represents the unique row identifier for each applicant in the dataset.</td>
  </tr>
  <tr>
    <td>GRE Scores (out of 340)</td>
    <td>This column contains the GRE (Graduate Record Examination) scores of the applicants, which are measured on a scale of 0 to 340.</td>
  </tr>
  <tr>
    <td>TOEFL Scores (out of 120)</td>
    <td>This column includes the TOEFL (Test of English as a Foreign Language) scores of the applicants, which are measured on a scale of 0 to 120.</td>
  </tr>
  <tr>
    <td>University Rating (out of 5)</td>
    <td>This column indicates the rating or reputation of the university that the applicants are associated with. The rating is based on a scale of 0 to 5, with 5 representing the highest rating.</td>
  </tr>
  <tr>
    <td>Statement of Purpose (out of 5)</td>
    <td>This column represents the strength of the applicant's statement of purpose, rated on a scale of 0 to 5, with 5 indicating a strong and compelling SOP.</td>
  </tr>
  <tr>
    <td>Letter of Recommendation Strength (out of 5)</td>
    <td>This column represents the strength of the applicant's letter of recommendation, rated on a scale of 0 to 5, with 5 indicating a strong and compelling LOR.</td>
  </tr>
  <tr>
    <td>Undergraduate GPA</td>
    <td>This column contains the undergraduate Grade Point Average (GPA) of the applicants, which is measured on a scale of 0 to 10.</td>
  </tr>
  <tr>
    <td>Research Experience (either 0 or 1)</td>
    <td>This column indicates whether the applicant has research experience (1) or not (0).</td>
  </tr>
  <tr>
    <td>Chance of Admit (ranging from 0 to 1)</td>
    <td>This column represents the estimated probability or chance of admission for each applicant, ranging from 0 to 1.</td>
  </tr>
</table>



## Performed following Tasks
1. Data Cleaning
2. Analysis
3. Visualization

- Observations on the shape of data, data types of all the attributes, conversion of categorical attributes to 'category', missing value detection, statistical summary

- Non-Graphical Analysis: Value counts and unique attributes ​
- Visual Analysis - Univariate, Bivariate after pre-processing of the data
- For continuous variable(s): Distplot, countplot, histogram for univariate analysis 
- For categorical variable(s): Boxplot 
- For correlation: Heatmaps, Pairplots 
- Missing Value & Outlier check

- Insights based on Non-Graphical and Visual Analysis
  
    . Comments on the range of attributes
  
    . Comments on the distribution of the variables and relationship between them
  
    . Comments for each univariate and bivariate plot

- **Answering questions-**
  

**1. Data Preprocessing** 
- Duplicate value check
- Missing value treatment
- Outlier treatment
- Feature engineering
- Data preparation for modeling


**2. Model building** 
- Build the Linear Regression model and comment on the model statistics
- Display model coefficients with column names
- Try out Ridge and Lasso regression


**3. Testing the assumptions of the linear regression model (50 Points)**
- Multicollinearity check by VIF score (variables are dropped one-by-one till none has VIF>5) 
- The mean of residuals is nearly zero 
- Linearity of variables (no pattern in the residual plot) 
- Test for Homoscedasticity 
- Normality of residuals (almost bell-shaped curve in residuals distribution, points in QQ plot are almost all on the line) 


**4. Model performance evaluation** 
- Metrics checked - MAE, RMSE, R2, Adj R2
- Train and test performances are checked
- Comments on the performance measures and if there is any need to improve the model or not
  
<br/> 

**Business Insights and Recommendations** based on significance of predictor variables and additional data sources for model improvement, model implementation in real world, potential business benefits from improving the model (These are key to differentiating a good and an excellent solution).
