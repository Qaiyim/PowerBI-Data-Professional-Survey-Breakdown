# Power BI Survey Breakdown
The report contains a single page with several visualizations focused on survey data, specifically related to job titles, salaries, and satisfaction.

## Executive summary 
This report analyzes a comprehensive survey of "Data Professionals" to understand the current landscape of the industry. It synthesizes salary data, technical preferences (programming languages), and workplace sentiment (work/life balance and salary satisfaction). The analysis reveals that while salary varies significantly by job title, overall career satisfaction is influenced heavily by regional factors and the ease of "breaking into" the industry.

## Business problem
The data industry is rapidly evolving, leading to three primary challenges for both employers and professionals:

- Compensation Benchmarking: Lack of clarity on how different roles (e.g., Data Analyst vs. Data Engineer) are compensated globally.
- Skill Gap Identification: Understanding which programming languages are actually favored by practitioners to guide training and hiring.
- Retention & Sentiment: Identifying the "happiness gap" in salary and work-life balance to reduce turnover in technical departments.

## Methodology
The analysis was conducted using Power BI to process survey responses from a "Data Professional Survey" dataset. The following steps were taken:

- Data Aggregation: Raw survey responses were cleaned and categorized by Job Title, Country, and Gender.
- Metric Calculation: Average salaries were calculated by role to normalize the data. Satisfaction scores were aggregated using gauge visualizations to measure sentiment against a predefined scale (0-10).
- Categorical Analysis: Treemaps and Donut charts were utilized to identify the geographic concentration of talent and the perceived difficulty of entering the data field.

## Skills Analyzed
The report highlights a specific set of technical and soft skills/factors currently dominating the field:

- Programming Languages: Quantitative tracking of "Favorite Programming Languages" (typically Python and SQL in this dataset).
- Data Literacy: The ability to navigate different data roles (Data Scientist, Analyst, Engineer).
- Domain Adaptation: Understanding how geographic location (Country) impacts earning potential and career progression.

## Result & Findings
- Salary Distribution: Salary is highly correlated with specific job titles. Certain specialized roles (likely Data Engineers or Architects) show higher average compensation than entry-level Analyst roles.
- Tech Preference: There is a clear "favorite" programming language among voters, indicating a industry-standard toolset that most professionals prioritize.
- Barrier to Entry: A significant portion of the workforce found it "difficult" or "very difficult" to break into the data industry, highlighting a high barrier to entry despite high demand.
- Sentiment Metrics:
  - Salary Happiness: The gauge suggests that happiness with pay is often lower than the mid-point, suggesting a desire for higher compensation across the board.
  - Work/Life Balance: Professional satisfaction with coworkers and balance varies, but generally tracks higher than salary satisfaction.

![image alt](https://github.com/Qaiyim/PowerBI-Data-Professional-Survey-Breakdown/blob/76106a7f03a44e6925d391d9d42ab9b27c66ffbf/PBI%201.png)

## Recommendations
- For Candidates: Focus on the "Favorite Programming Language" identified in the report (Python/SQL) to increase marketability, as these are the tools currently used by the majority of successful professionals.
- For Employers: Address the "Salary Happiness" gap by benchmarking against the "Average Salary by Job Title" visual. If your internal salaries are below these averages, retention risk is high.
- For Educators: Develop bridge programs or junior-level certifications to lower the "Difficulty to Break In," as the data suggests a bottleneck for new talent entering the field.
- Strategic Localization: Companies should look for talent in the high-density countries identified in the Treemap to tap into established hubs of data expertise.
