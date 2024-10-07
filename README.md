# Data Salaries Analysis

## Overview
This project provides a comprehensive analysis of salaries in the data science field using a dataset containing global job positions, salaries, and employment information. By performing exploratory data analysis (EDA), we uncover key insights into the highest-paying job titles, locations with the best compensation, and remote work trends within the industry.

The dataset used in this project is publicly available and contains detailed salary information across various job titles, company locations, and experience levels.

### Key Features

- Data Cleaning: The dataset was thoroughly cleaned by removing duplicate entries and handling missing values to ensure accuracy in the analysis.
- Salary Insights: We identify the top-paying job titles and analyze the geographical locations of companies that offer the highest compensation.
- Remote Work Analysis: Insights into job titles that offer the highest percentage of remote work, as well as country-level trends.
- Experience Level Comparison: Analysis of average salaries across different experience levels and job titles, with special focus on specific roles like Data Scientist and Data Modeler.
- Visualizations: Multiple visualizations, including bar charts and pie charts, were created to better communicate findings and trends.

### Table of Contents
- [Data](#Data)
- [Cleaning and Preprocessing](Cleaning and Preprocessing)
- [Exploratory Data Analysis](#Exploratory Data Analysis)
    - Top-Paying Job Titles
    - Company Locations and Salaries
    - Remote Work Trends
    - Experience Levels and Salary Comparison
- [Visualizations](#Visualizations)
- [Conclusion](#Conclusion)

### Data
The dataset used in this analysis consists of global salary data for various job titles in the data science field. Key columns include:

- job_title: The title of the job (e.g., Data Scientist, ML Engineer)
- salary_in_usd: The salary converted to USD for consistency
- company_location: Country where the company is located
- remote_ratio: The percentage of the job that is remote (0%, 50%, 100%)
- experience_level: Experience level (Entry, Junior, Senior, Executive)

### Cleaning and Preprocessing
- Duplicates: We identified and removed 1,171 duplicate records, resulting in a clean dataset of 2,584 unique entries.
- Missing Values: Checked for null values across all columns and confirmed that the dataset is complete with no significant missing data.

### Exploratory Data Analysis

#### Top-Paying Job Titles
Using average salary by job title, we determined the highest-paying roles in the dataset. The top 10 job titles include roles such as Data Scientist, Machine Learning Engineer, and Data Architect, with the highest salaries reaching over $200,000 annually.

#### Company Locations and Salaries
We explored the geographic locations of companies offering the highest salaries. Companies located in [Country with highest salaries] have the highest average salaries, with compensation well above the global average.

#### Remote Work Trends
A key analysis in this project is determining which job titles and countries offer the most remote work opportunities. Our findings show that some roles, such as [Top Remote Job Title], are predominantly remote, with a remote work percentage of up to 100%.

#### Experience Levels and Salary Comparison
The dataset was segmented by experience levels to analyze salary trends across junior, mid-level, and senior roles. For instance, Data Scientists at a Senior level (SE) earn significantly more than their junior counterparts.

### Visualizations

We utilized various visualizations to enhance the understanding of the dataset:

- Bar Charts: Used to visualize top salaries by job title and remote work trends by country.
- Pie Charts: Highlighted the proportion of workers earning above and below $200,000, and the distribution of employment types among Business Data Analysts.
- Comparative Analysis: Graphs comparing the average salaries of Data Scientists to all other job titles, as well as full-time vs part-time salary differences for ML Engineers.

Figure 1: Top 10 job titles by average salary

Figure 2: Top 20 job titles offering remote work

### Conclusion

This analysis provides valuable insights into salary trends within the data science industry, including:

- Top-paying roles and locations: Identifying key roles that offer the highest salaries and the countries where companies are paying the most.
- - Remote work opportunities: Revealing job titles that offer the highest percentages of remote work, and countries where remote work is most prevalent.
- Experience-based salary comparison: Highlighting the salary differences across experience levels and job titles.
- The findings from this project can be useful for data professionals looking to benchmark salaries, as well as companies looking to understand global salary trends in data science roles.

### How to Run the Notebook

1. Clone this repository:
```
git clone https://github.com/username/repository-name.git
Install the required dependencies:
```


### License
This project is licensed under the MIT License.

### Author
- **Name**: Rosalía González Caviedes
- **Email**: rosaliagonzalezc@gmail.com
- [LinkedIn profile](https://www.linkedin.com/in/rosaliagonzalezcaviedes/)
- [Github profile](https://github.com/liagcaviedes)
