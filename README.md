Objective: To analyze salary data for Business Analyst jobs in Hong Kong by scraping job portals.

Data Source : JobsDB website (https://hk.jobsdb.com/business-analyst-jobs/full-time).

Data Collection:
  Tools: Python, BeautifulSoup, Requests.
  Process: Scraped job details, cleaned data, handled missing values.
  
Data Visualization :Visualized salary distribution, salary vs. job title, location, company, and industry.

Insights:
  Identified salary trends and high-paying job titles.
  Analyzed geographical and company-specific salary variations.
  Assessed industry demand for Business Analysts.
  
Challenges : 
  Faced 403 errors on other job portals; successfully used JobsDB.
  Predictive Modeling Considerations
  Limited data for robust predictive modeling.
  Imputed missing values may bias results.
  
Conclusion : Despite challenges, the project provided key insights into Business Analyst salaries in Hong Kong. Further data collection and predictive modeling can enhance findings.

How to Run the Project-

Install Libraries:
  bash
  Copy code
  pip install requests beautifulsoup4 pandas scikit-learn seaborn matplotlib
  
Run Scripts:
  data_collection.py: Scrape data.
  data_cleaning_analysis.py: Clean and analyze data.
  visualization.py: Generate visualizations.
  predictive_modeling.py: Predict salaries.
  
Dataset:
  final.csv: Collected and cleaned data.
  
Notes:
  Ensure permission for web scraping.
  Handle data integrity carefully.
  Validate results with domain experts.
