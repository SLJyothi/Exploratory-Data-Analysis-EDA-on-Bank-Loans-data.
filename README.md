# Exploratory-Data-Analysis-EDA-on-Bank-Loans-data.
A comprehensive dataset for analyzing loan-related data using Python. Includes information on loan amounts, interest rates, borrower demographics, and repayment status. Ideal for exploring statistical patterns, risk assessment, and building predictive models in financial analytics.Develops banking variables for financial analysis. Utilizes Python to create robust tools for transaction analysis, risk assessment, and customer profiling. Enhances decision-making processes through comprehensive data insights, improving financial strategies and performance

## Importing Libraries
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/41f825d5-0113-4c36-a537-566deed7095f)

There are 2500 records for 15 variables.

## Databases Used:
['LoanID', 'Amount.Requested', 'Amount.Funded.By.Investors', 'Interest.Rate', 'Loan.Length', 'Loan.Purpose', 'Debt.To.Income.Ratio', 'State', 'Home.Ownership', 'Monthly.Income', 'FICO.Range', 'Open.CREDIT.Lines', 'Revolving.CREDIT.Balance', 'Inquiries.in.the.Last.6.Months', 'Employment.Length'],
These columns are essential for Python-based data analysis in finance. They encompass crucial loan parameters such as requested and funded amounts, interest rates, loan length, purpose, borrower demographics, credit history, and employment details. Through Python, comprehensive analysis enables informed decision-making and risk assessment in financial lending processes.

## EDA: Exploratory Data Analysis
Conducting Exploratory Data Analysis (EDA) on the dataset to prepare it for effective data analysis. This process involves understanding data distributions, identifying patterns, handling missing values, outliers, and ensuring data quality. By cleaning, transforming, and visualizing data, EDA enhances its usability and enables meaningful insights for further analysis.

## Step1: Variables names following the Naming Convention,

![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/743aac4c-96ab-4e2f-8ab1-7bc5b521cd36)

![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/80dc359f-eb34-4a9f-b79c-8998ba3dfadc)
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/4d9ba614-efa6-4e80-b208-68b9b8a59b3b)

Performing naming conventions on a dataset is crucial for enhancing its clarity and usability in data analysis tasks. This process involves standardizing the case style, removing special characters, shortening lengthy names, and ensuring consistency across all variables or columns. Descriptive names that clearly convey the content or meaning of each variable are preferred, avoiding conflicts with reserved words. Documentation of the naming conventions used facilitates future reference, maintaining the dataset's clarity and ease of use

## Step 2: Check the information: Data type Conversions
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/fec86424-f818-4074-8621-a597a1a2514a)
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/030e4702-90de-4d0c-a02d-b6ed95c67041)
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/91def4e5-f7bc-42c4-8aba-e206702c4609)
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/063ffc68-9839-472e-884a-b0a08b2427ba)

## Data type conversions:
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/89007c98-bf9a-4010-8deb-e0af16caf11d)
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/37e1a19e-4cd8-4313-a254-aa18b072f927)

Performing data conversion to align with required analysis involves transforming raw data into a format suitable for the analytical techniques and methods planned for the project. This may include converting data types, aggregating or disaggregating data, standardizing units of measurement, and handling missing or erroneous values. By tailoring the data to meet the specific requirements of the analysis, it becomes more conducive to deriving meaningful insights and drawing accurate conclusions

## Checking the relevant and irrelevant variables in the first phase of EDA:

![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/2d48daaf-8bf3-4a38-a898-96c76caad825)

![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/ec0e0ac8-b9d4-4072-9de8-f60fe2675006)
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/6299fe3a-e2c3-432f-8592-b46d25c09b1b)

## Distribution of customers by State:
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/46782fd1-c363-416b-95b1-31f36018cfb7)
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/2916fe00-609b-4cec-ab44-a92d6e0bcbb2)

This code snippet prints the value counts of the 'State' column in the dataset and visualizes the distribution of customers by state using a bar plot. The printed counts provide insights into the frequency of occurrence of each state in the dataset, while the bar plot offers a graphical representation of this distribution, facilitating easier interpretation and analysis.

![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/7ba3d17e-61fe-4728-9658-f49e6bbdd7ef)
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/3727d6ab-421b-4983-896a-a14acb3caa02)

This code snippet calculates the value counts of the 'Loan_Purpose' column in the dataset, providing insights into the frequency of each loan purpose. Subsequently, it visualizes the distribution of customers by their loan purpose using a bar plot, where each bar represents the number of customers associated with a specific loan purpose. The plot aids in understanding the distribution pattern and identifying predominant loan purposes among customers. The code employs the matplotlib library for plotting, setting appropriate labels for clarity, and ensures readability by specifying the figure size.

![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/7f0c22b2-49cb-45f4-bbc2-b3d57645b378)

This code segment prints the value counts of the 'Home_Ownership' column in the dataset, revealing the frequency of each home ownership category among customers. It then generates a bar plot to visualize this distribution, providing insights into the distribution pattern and predominant types of home ownership among customers. The matplotlib library is utilized for plotting, and appropriate labels are set for clarity, while the figure size is specified for readability.

## Data Duplicacy: Chech if their is duplicate data or not: DDT ( Data Duplicacy Treatment)
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/852a5072-b2d2-4f2b-aba0-a1afb5ed9975)

Performing data deduplication involves identifying and removing duplicate records within a dataset. This process ensures data integrity and accuracy by eliminating redundant information. Using Python's pandas library, duplicate rows are detected and removed based on specified columns. The resulting dataset contains only unique records, optimizing data quality for subsequent analysis. By comparing the shape of the original and deduplicated data, insights into the extent of duplication can be gained, facilitating further data refinement and analysis.

## Missing Values Treatment:
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/b1ef3417-1a9a-4985-8b96-276ff5ea4d7a)

Performing missing values treatment is a crucial step in data preprocessing, essential for ensuring the integrity and reliability of subsequent analyses. This process involves identifying missing values within the dataset using pandas functions like isnull() or info(), followed by determining the most appropriate method for handling them. Imputation techniques, such as replacing missing values with mean, median, or mode, offer a common approach, while deletion strategies involve removing rows or columns with missing data. Validation of the treatment's effectiveness is vital, typically achieved by rechecking for missing values post-treatment. Documenting the entire process enhances transparency and reproducibility, facilitating robust data analysis and interpretation.

## Creating a UDF which can automate the missing value treatment.

![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/fc2a79b5-fa0b-4c44-b3ff-c4eaab972f28)
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/f735aa69-2cd9-410e-ba23-df4e8f4b930c)

The miss_value_treat function is a user-defined function (UDF) designed to treat missing values in a pandas Series object s. This function employs conditional logic to differentiate between object (categorical) and non-object (numerical) data types within the Series. For object type data, missing values are imputed with the mode (most frequent value), while for numerical data, missing values are filled with the median. The function provides a versatile and automated approach to handle missing data effectively, enhancing data integrity and enabling seamless analysis.

## Separating the categorical Variables and Numerical variables into two different datasets for Data Preparations for Data Analysis.
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/37a4519d-5d67-4abd-a11c-2bb1e520be66)

The code snippet identifies categorical and numerical variables within a dataset using list comprehensions in Python. For categorical variables, it iterates through the columns and selects those with object data type ('O'). Similarly, for numerical variables, it identifies columns with non-object data types. This approach efficiently categorizes variables based on their data types, facilitating tailored data analysis and preprocessing. By separating variables into categorical and numerical groups, it enables targeted treatment and exploration, enhancing understanding and insights from the dataset.

## Filling missing values in Numerical data with the Median values.
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/bfbc0e29-dd8b-43cd-b9ae-e28c994d9c5a)

The code iterates through each column in a DataFrame containing numerical data (num_data). For each column i, missing values are filled using the median value of that column. This process ensures that missing values in numerical columns are replaced with a central tendency measure, mitigating their impact on subsequent analyses. By applying this treatment across all numerical columns, the code enhances data completeness and integrity, enabling more robust statistical analysis and modeling.

## Filling missing values in Categorical data with the Mode values.
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/434691f2-d7cc-4de6-a612-52ea648f570c)
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/ca581d85-bbb3-43bf-b0a0-aa3a6c28e325)
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/29d2db0a-c5ac-462b-9036-69d251f3a2cb)
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/913a84bb-80cc-4f88-8d78-dd28ff750932)

This code iterates through each column in a DataFrame containing categorical data (cat_data). For each column i, missing values are filled using the mode (most frequent value) of that column. This approach ensures that missing categorical values are replaced with the most common category, preserving the distribution of categorical variables. By applying this treatment across all categorical columns, the code enhances data completeness and prepares the dataset for further categorical analysis or modeling.

## Outlier Treatment
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/53b3186d-cd08-4632-8b38-2316fc450045)

## Just observing a single column for the outliers
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/6905dfd8-101e-4270-b49d-ab6669c88230)

## quantile() helps to find the percentile vaues at each percentile mark.
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/644f2227-1d28-477c-b257-e4820d210617)
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/4a031a3d-a3e9-4b9b-9e47-63ba75802d1d)
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/669d4d8a-11c3-4f0b-bf13-e166d79ca4fa)
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/0940474b-b96e-4bf2-9e56-e475f3175ce4)
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/b47315ed-7287-47e0-a488-897bf7e7574e)
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/047fbbe9-fa60-4b8e-aa6c-841ea7f6fc4e)

## Outlier treatment IQR Method
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/0fd2436c-183f-41ae-bdf1-747d6748eb4b)
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/ec7935f4-6381-4c12-a530-37c31da29bd5)

## Outlier treatment of only required columns,
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/13d32ed3-58ee-47b7-9cbd-9ec1f6be15e4)
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/eb5a2616-4488-4e35-8fd9-2a25993794c2)
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/9952602a-0f63-47fa-97cf-289cac04e8e2)
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/4162dfce-cf7f-4083-81f1-22403630df82)
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/ee69abf2-bd5b-40d8-a6d3-e9c277b6e63f)
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/7089de3b-6167-4dca-947d-6f2164cac8e6)
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/8a6b770d-13a7-4a15-9074-8ec6baddd167)

Detecting and treating outliers is crucial in data analysis to ensure the accuracy and reliability of statistical models. The Interquartile Range (IQR) method provides a robust approach for identifying outliers by calculating the range between the first and third quartiles. Data points lying outside the range of 1.5 times the IQR above the third quartile or below the first quartile are flagged as outliers. Subsequently, these outliers can be treated through various methods, such as replacing them with central tendency measures like the median or removing them entirely, depending on the dataset's characteristics and analysis objectives. This process enhances the quality of data analysis and improves the validity of insights derived from the dataset.

## Outlier treatment on all columns in num_data_2b
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/2a5f11d0-763f-4701-b2a8-e655360c53ad)
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/8185bae3-0e0d-4198-9ffb-30c9e0899e76)
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/de88b436-b222-4ccb-8ec5-a78fcca03c40)

## Merging the categorical and the numerical data to get the dataset
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/df335dc1-e362-4393-9124-a1cd6c856922)

Merging categorical and numerical data in Python involves combining datasets based on a common column or index using joins. Leveraging the merge() function from the pandas library enables seamless integration of disparate data types. This process facilitates comprehensive analysis by consolidating information from multiple sources into a unified dataset. By specifying join conditions and column identifiers, categorical and numerical data are merged into a cohesive structure, streamlining subsequent analytical workflows. Whether employing inner, outer, left, or right joins, this approach ensures the effective utilization of data across various domains, enhancing insights and decision-making capabilities.

## One-Hot Encoding: Conversion of categorical variables to continuous variables.

![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/59ba0f6e-d582-424f-a49d-c295fc403018)
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/bdff2f1a-4ec0-4f1d-885f-a4e56942124c)
![image](https://github.com/SLJyothi/Exploratory-Data-Analysis-EDA-on-Bank-Loans-data./assets/164232591/d0ce337c-0f95-4b54-a49b-97824b5bd9a6)

The code employs the get_dummies() function from the pandas library to conduct one-hot encoding on categorical variables within the DataFrame M_data1a. Specifically, it targets the 'Home_Ownership' and 'Loan_Purpose' columns, converting them into binary representations of their categories. This process generates new binary columns for each unique category present in the original columns, effectively transforming categorical variables into continuous ones. By encoding categorical data in this manner, the DataFrame becomes suitable for consumption by machine learning algorithms, facilitating predictive modeling and analysis tasks.

## Conculsion

The process of data analysis in Python begins with exploratory data analysis (EDA), a crucial step to understand the dataset's structure, features, and underlying patterns. Through descriptive statistics and visualizations like histograms and correlation matrices, analysts gain insights into relationships and distributions within the data. Following EDA, attention turns to data preprocessing tasks, including changing column names for improved clarity and treating missing values. Missing values, identified using functions like isnull(), are often imputed using methods such as mean, median, or mode. Visualizations, such as heatmaps or bar plots, aid in understanding the distribution and patterns of missing values within the dataset. Additionally, categorical variables are transformed into a suitable format for machine learning algorithms through one-hot encoding. This involves creating binary columns for each category using functions like get_dummies(), facilitating the seamless integration of categorical data into predictive modeling workflows. Overall, this iterative process equips analysts with the tools necessary to derive meaningful insights and make informed decisions from their datasets.
