# Tech Salary Analysis
Unlock the secrets of developer earning power! This project dives deep into the Stack Overflow Developer Survey 2023 to uncover the relationships between compensation, experience, education, location, and tech skills. 

## Objectives
1. Analyze the correlation between higher salaries and factors such as coding experience, specialized tech skills, using correlation analysis and visualizations.
2. Develop a regression model to estimate real income based on predictor variables like primary coding language, years of professional experience, company size, region, etc.
3. Perform statistical hypothesis testing to:
    a. Examine if AI skills and education levels have higher associated wage points.
    b. Ascertain whether coding skills, including tech stack familiarity and usage, impact earning potential.
    c. Analyze the dependency of online courses/certifications on the developer's highest level of formal education.
    d. Analyze how programming language preferences among developers vary with age or experience levels.
4. Provide suggestions on various skills, geographies, and roles associated with higher real income, and identify skills with high return on investment.

## Getting Started
1. Clone this repository to your local machine.
2. Install the required Python libraries: NumPy, Pandas, Matplotlib, Seaborn, Keras, and scikit-learn.
3. Download the Stack Overflow Developer Survey 2023 dataset and place the CSV file in the data/stack-overflow-developer-survey-2023 folder.
4. Fire up your Jupyter Notebook and navigate to the project directory.
5. Run the analysis notebook and let the insights unfold!
Here's a clearer and more interesting version of the README file for your tech salary analysis project:


## Methodology
1. Datasets: Stack Overflow Developer Survey 2023 (approx. 47,000 validated responses after data cleaning), Numbeo's Cost of Living Index, XE.com currency conversion rates
2. Data cleaning: Missing data, irrelevant columns, and outliers removed
3. Feature engineering: Compensation figures converted to USD, to adjust for cost of living to get real income (a true measure of purchasing power)
4. Regression models: CatBoost Regression, Random Forest Regression, Gradient Boosting Regression, and more
6. Correlation analysis, hypothesis testing, and data visualization techniques


## Key Findings
1. Professional coding experience is the most influential factor on real income, with a strong positive correlation.
2. Remote work may lead to higher adjusted earnings compared to in-office roles.
3. Developers proficient in languages like Go, Ruby, and Bash/Shell tend to earn more.
4. Specific technologies like AWS, Terraform, and Kubernetes are associated with higher real income.
5. Leadership positions (Senior Executives, Engineering Managers) command higher compensation.
6. Geographic location and currency disparities significantly impact the real income of developers.
7. Age groups 35-44 years, 55-64 years, and 25-34 years tend to have the highest maximum compensation packages.
8. AI skills do not necessarily guarantee higher earnings (yet), potentially due to the nascent adoption stage.

