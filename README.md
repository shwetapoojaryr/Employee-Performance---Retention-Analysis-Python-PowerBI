<img width="609" height="787" alt="image" src="https://github.com/user-attachments/assets/839cec72-f0f7-4bf4-bc2b-92b5fa82f79e" /><img width="649" height="467" alt="image" src="https://github.com/user-attachments/assets/6c09f80e-470d-4d20-8bd6-fd931d2bbbaa" /># Employee-Performance-and-Retention-Analysis

Analysed employee performance and retention patterns using HR data to uncover factors influencing productivity, engagement, and employee tenure, to help organizations reduce turnover and improve workforce efficiency through data-driven insights using Python, Jupyter Notebook, and Power BI.

## Table of Contents
- <a herf = "#overview">Overview</a>
- <a herf = "#business-problem">Business Problem</a>
- <a herf = "#dataset">Dataset</a>
- <a herf = "#tools--technologies">Tools & Technology</a>
- <a herf = "#project-structure">Project Structure</a>
- <a herf = "#data-cleaning--preparation">Data Cleaning & Preparation</a>
- <a herf = "#exploratory-data-analysis-eda">Exploratory Data Ananlysis (EDA)</a>
- <a herf = "#research-factors">Research Factors</a>
- <a herf = "#key-findings">Key Findings</a>
- <a herf = "#key-metric-analysis">Key Metric Analysis</a>
- <a herf = "#dashboard">Dashboard</a>
- <a herf = "#how-to-run-this-project">How to Run this Project</a>
- <a herf = "#final-recommendations">Final Recommendations</a>
- <a herf = "#author--contact">Author & Contact</a>

<h2><a class="anchor" id="overview"></a> Overview</h2>

This project focuses on analysing employee performance and retention patterns within an organisation. By leveraging HR data, the goal is to identify key factors influencing employee productivity, performance, and retention, and provide actionable insights for improving workforce efficiency, reducing turnover, and fostering a positive work environment. The project will employ data analysis techniques, including exploratory data analysis (EDA), trend analysis, and visualisation to help HR managers make data-driven decisions for workforce management. 

<h2><a class = "anchor" id="business-problem"></a>Business Problem</h2>

The objective of this project is to analyse HR data to assess employee performance, identify trends influencing retention, and provide recommendations for improving employee productivity and reducing turnover.

Specifically, the project aims to: 

● Identify performance patterns based on factors such as age, education, department, and training. 

● Examine retention trends based on employee characteristics such as tenure, performance ratings, and awards. 

● Provide recommendations for improving employee engagement and retention strategies by analysing the relationship between key employee metrics. 

<h2><a class ="anchor" id ="dataset"></a>Dataset</h2>

[Employee Dataset](https://github.com/shwetapoojaryr/Employee-Performance---Retention-Analysis-Python-PowerBI/blob/main/employees_dataset.csv)

- Rows: 17417
- Columns: 13
- Key Features :  Employee Identifier (employee_id), Organizational Attributes (department, region), Demographic Features (education, gender, age), Recruitment Information (recruitment_channel), Training & Development (avg_training_score, no_of_trainings), Performance Metrics (KPIs_met_more_than_80, previous_year_rating), Recognition & Experience (length_of_service,  awards_won)
- Missing Data: 771 values in education column & 1363 in previous_year_rating column. 

<h2><a class ="anchor" id ="tools--technologies"></a>Tools and Technologies</h2>

- Python (Pandas, Matplotlib, Seaborn, Scipy)

- Jupyter Notebook

- Power BI (Interactive Visualisations)

- GitHub

<h2><a class="anchor" id ="project-structure"></a>Project Structure</h2>


<h2><a class="anchor" id ="data-cleaning--preparation"></a>Data Cleaning & Preparation</h2>

**Data Preprocessing**

Handling of the missing values with fillna(), median(), & mode () functions 
<img width="448" height="403" alt="image" src="https://github.com/user-attachments/assets/583dee76-6786-44db-9f4f-073eb9c79a5a" />

Encoding Categorical variables and ensuring consistency in data formatting.
<img width="693" height="202" alt="image" src="https://github.com/user-attachments/assets/9d0f3386-04eb-46b5-9a07-afde7386cd42" />

<h2><a herf = "#exploratory-data-analysis-eda"></a>Exploratory Data Ananlysis (EDA)</h2>

Initial Exploration: Used df.info() to check structure and .describe() for summary statistics.  
<img width="815" height="744" alt="image" src="https://github.com/user-attachments/assets/66edda40-52b7-4b4a-9f27-bd2a3b0f0d60" />

Found the missing and duplicate values in the dataset using isnull() and duplicated() functions. 
<img width="440" height="515" alt="image" src="https://github.com/user-attachments/assets/a4cef920-6129-4be8-9af7-47195dfab961" />

Found the distribution of key numerical variables and categorical variables 
<img width="722" height="548" alt="image" src="https://github.com/user-attachments/assets/2f09eec0-e94e-42b0-818b-bed9b0441800" />
<img width="631" height="804" alt="image" src="https://github.com/user-attachments/assets/246a3c2f-cbf3-4d06-a293-15f408f72de7" />
<img width="693" height="810" alt="image" src="https://github.com/user-attachments/assets/e38aca46-9b78-4a17-b8f1-9944c1ef8fe1" />
<img width="649" height="467" alt="image" src="https://github.com/user-attachments/assets/5e40f40e-d1ab-4b0b-9a7d-db5b85d70c24" />

<h2><a class= "#research-factors"></a>Research Factors</h2>

**Key Metrics Analysis: Analyse key performance and retention metrics such as length of service, average training score, awards won, previous year ratings, and KPIs met.**

**Retention Trends Analysis: Assess retention trends based on age, education, department, and training.**

**Predictive Insights: Based on the analysis, provide actionable recommendations to HR for improving employee retention and performance management strategies.**

<h2><a class= "#key-findings"></a>Key Findings</h2>

- Employees with higher training scores and KPI achievement show longer retention 

- Award-winning employees consistently outperform peers 

- Mid-career age groups (30–40) show the highest retention 

- Certain departments have shorter service lengths, indicating engagement gaps 

- Employees with lower previous year ratings are more likely to exit early

**Workforce Overview**
- Employees are mostly in the early to mid-career range (20–40 years). 
- Distribution across departments and regions varies, highlighting operational concentration risks. 
- Recruitment channels influence performance outcomes, indicating differences in candidate quality.

**Performance Insights**
  
- High training scores, KPI achievement, and awards strongly correlate with better performance. 
- Consistent performers continue to excel year-over-year. 
- Departments with lower performance may need targeted interventions.

<h2><a class= "#key-metric-analysis"></a>Key Metric Analysis</h2>

Summarizing performance metrics by creating a performance_metrics table 
<img width="721" height="308" alt="image" src="https://github.com/user-attachments/assets/6b80df18-c3f9-4d93-99a1-a33934e8ddda" />

Analysing key metrics such as KPI Achievements vs performance, awards impact on performance,length of service analysis 
<img width="567" height="401" alt="image" src="https://github.com/user-attachments/assets/55d05b54-834b-4431-839f-926234708888" />
<img width="609" height="787" alt="image" src="https://github.com/user-attachments/assets/34dd9892-0d09-4acf-a007-3591ea32ad39" />

 Retention Trends Analysis 
● Trend analysis assuming longer length of service = higher retention 
● Analysing retention by age group, education, department, training impact on retention. 
<img width="649" height="812" alt="image" src="https://github.com/user-attachments/assets/748587ad-9e93-4d71-b3f8-dfa197e01034" />
<img width="685" height="836" alt="image" src="https://github.com/user-attachments/assets/c232ead2-f2af-442a-8d03-e17f9d78a4ff" />

**Retention Trends Insights**
- High retention: Employees aged 30–40, award winners, and consistent KPI achievers. 
- Retention risk: Early-career employees (20–30), low KPI achievers, and employees in certain departments with shorter tenure. 
- Effective training and recognition directly improve retention.

<h2><a class= "#Dashboard"></a>Dashboard</h2>
<img width="1311" height="734" alt="image" src="https://github.com/user-attachments/assets/af233421-224e-4531-9bb3-8746dbb9aac6" />
<img width="1304" height="373" alt="image" src="https://github.com/user-attachments/assets/26111dfd-b372-45a7-be74-41dc1041581e" />

<h2><a class= "#how-to-run-this-project"></a>How to Run this Project</h2>


<h2><a class= "#final-recommendations"></a>Final HR Recommendations</h2>

1. Increase targeted training programs for low-performing departments. 

2. Introduce recognition programs to improve motivation and retention. 

3. Focus retention strategies on early-career employees (20–30 age group). 

4. Use KPI performance as an early indicator for engagement interventions. 

5. Invest in continuous learning for employees with high potential but low ratings. 

<h2><a class= "#author--contact"></a>Author & Contact</h2>

**Shweta Poojary**

Data Analyst

Email: [shwetapoojarywm@gmail.com](mailto:shwetapoojarywm@gmail.com)

[LinkedIn](https://www.linkedin.com/in/shweta-p-176861295/)

[Portfolio]()
