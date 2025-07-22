# Minimum Wage Analysis
    This project explores global minimum wage trends using Python and publicly available datasets from Kaggle and Excel. The goal is to compare nominal and purchasing power parity (PPP)-adjusted wages, analyze working hours, and identify regional disparities.
    # Tools & Technologies
    - Python (Pandas, NumPy, Matplotlib, Seaborn)
    - Jupyter Notebook
    - Kaggle Datasets
    - Excel (XLSX, CSV)
    # Skills 
    - Data collection and import (from Kaggle and Excel)
    - Data cleaning and preprocessing
    - Grouping and aggregation by country and continent
    - Correlation analysis between nominal and PPP wages
    - Data visualization for storytelling
    - Insight generation based on economic patterns
    # Key Insights
    - Comparison of average working hours across continents
    - Relationship between nominal wages and PPP wages
    - Visual representation of wage disparities worldwide
    # File Structure


# Competitor Benchmarking Database
This project is a relational SQL-based system designed to help firms benchmark their financial performance against custom-selected competitors. 
Unlike static industry classification systems, this database allows users to define tailored competitor portfolios and generate dynamic financial comparisons.
    # Features
    - Firms can select their own competitors to create a custom benchmarking portfolio
    - Tracks financial metrics such as revenue, net income, growth rates, and ratios
    - Supports industry and sector classification with many-to-many flexibility
    - Built-in transaction log system for user activity tracking and audit trails
    
    # Schema Highlights
    - Tables: Firms, Industries, Sectors, Portfolios, Financial Metrics, Competitor Relationships, Benchmark History
    - Full normalization to BCNF
    - Supports dynamic reporting and comparative analysis
    
    # Use Cases
    - **Analysts** can define peer sets across industries to measure KPIs
    - **Auditors** can trace all changes made to firm records by user and time
    - **Investors** can query firms exceeding financial thresholds like debt-to-equity ratio
    - **Strategists** can track multi-industry firms across evolving portfolios
    
    # Sample Queries
    - Firms with the most recent debt-to-equity ratio above 0.7  
    - List of firms in both "Technology" and "Manufacturing" industries  
    - Portfolio summary: value and number of firms allocated  
    - Competitor lists by industry (e.g., all competitors of technology firms)
    
    # Database Design
    - **ER Diagram** with 20+ normalized tables
    - **SQL DDL scripts** with all primary & foreign key constraints
    - **Insert statements** for sample data population
    - Includes **transaction logging**, **user roles**, and **portfolio allocations**
    
    # Tools & Concepts Demonstrated
    - SQL DDL, DML, JOINs, subqueries, composite keys
    - BCNF normalization, relationship modeling
    - Business-driven database design for financial benchmarking
    
    # Target Users
    - Equity research analysts
    - Corporate strategy teams
    - Consultants and financial planners
    - Portfolio managers needing dynamic benchmarks
    
    #Conclusion
    This project showcases the power of customized data systems in competitive analysis. From schema design to query logic, it bridges theoretical database knowledge with practical business intelligence use cases.
