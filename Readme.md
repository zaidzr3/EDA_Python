# NYC Government Job Postings - Exploratory Data Analysis (EDA)

## Introduction
This project provides an Exploratory Data Analysis (EDA) of job postings data from NYC's official job portal. The analysis is aimed at uncovering patterns and insights from the data to better understand hiring trends, preferred skills, high demand job categories, salary patterns, and career level requirements. The findings can be used by job seekers to align their skills and application timing with opportunities in the NYC public sector.

## Project Overview
- **Dataset**: NYC Government Job Postings dataset obtained from the NYC Open Data Portal.
- **Objective**: Analyze job posting trends, salary distributions, career levels, and skills in demand.
- **Tools Used**: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, WordCloud.

## Steps of Analysis
1. **Data Cleaning**:
   - Removed duplicate job postings.
   - Dropped irrelevant columns (e.g., Recruitment Contact, Business Title).
   - Filled missing values in critical fields to prevent issues in text-based analysis.

2. **Data Preprocessing**:
   - Standardized all salary values to annual rates for uniformity.
   - Removed part-time roles to focus on full-time job opportunities.
   - Removed entries for career level "Student" to focus on professional opportunities.

3. **Feature Engineering**:
   - Created salary bins for categorizing roles as Low, Medium, High, and Very High.
   - Extracted Posting Year and Month to analyze temporal trends.
   - Mapped career levels to numeric values to facilitate correlation analysis.

4. **Data Visualization**:
   - **Univariate Analysis**: Career level distribution, job categories, top agencies, and salary bins.
   - **Bivariate Analysis**: Starting salary by career level and job category.
   - **Multivariate Analysis**: Correlation heatmap to understand relationships between salary, career level, and other factors.
   - **Temporal Analysis**: Analyzed monthly and yearly trends in job postings.
   - **Text Analysis**: Used CountVectorizer to extract and visualize the most common skills and qualifications in the job postings.

## Key Findings
- **High Demand Fields**: Significant demand in "Engineering, Architecture & Planning" as well as "Health" and "Legal Affairs".
- **Key Hiring Agencies**: Department of Environmental Protection and Health/Mental Hygiene.
- **Salary Patterns**: Most roles offer salaries ranging from $50,000 to $100,000, with higher salaries for executive positions.
- **Preferred Skills**: Strong focus on communication skills, educational qualifications, and Microsoft Office proficiency.
- **Hiring Trends**: Postings peak in October, possibly due to fiscal year-end cycles. An increasing trend in job postings is observed for the year 2024.

## Requirements
- Python 3.x
- Libraries: 
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-Learn
  - WordCloud
  - Jupyter Notebook (or Google Colab for running the notebook)


## Usage
1. **Clone the Repository**:
   ```sh
   git clone https://github.com/zaidzr3/EDA_Python.git
   ```

2. **Run the Jupyter Notebook**:
   - Open the notebook in Jupyter Lab or Google Colab.
   - Make sure the dataset is loaded in the correct path as expected in the notebook.

3. **View the Analysis**:
   - Step through the notebook to visualize trends and insights from the job postings data.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request for any features or improvements you would like to add. Let's make this project better together!

---
Thank you for exploring this EDA of NYC Government Job Postings. We hope these insights will be beneficial for job seekers and data enthusiasts alike!
