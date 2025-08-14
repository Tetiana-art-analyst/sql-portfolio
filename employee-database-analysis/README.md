# Employee Database Analysis

## 📊 Project Overview
Advanced SQL analysis of employee database containing salary, department, and career progression data. Demonstrates complex query techniques for HR analytics and business intelligence.

## 🎯 Business Questions Addressed
1. **Salary Trends**: How have average salaries changed over time?
2. **Department Analytics**: Which departments have highest compensation?
3. **Employee Insights**: Who are the top earners vs department averages?
4. **Management Analysis**: Historical management hierarchy and progression

## 🗃 Database Schema
The analysis uses a typical HR database with tables:
- `employees` - Personal information and hire dates
- `salaries` - Historical salary data with date ranges
- `departments` - Department information
- `dept_emp` - Employee-department relationships
- `titles` - Job titles and promotion history
- `dept_manager` - Management hierarchy

## 📈 Key Findings
- **Salary Growth**: Average salaries increased consistently until 2005
- **Department Leaders**: Identified highest-paying departments
- **Large Teams**: Found departments with 15,000+ employees
- **Management Tenure**: Analyzed management succession patterns

## 🔧 SQL Techniques Used
- **Window Functions**: `ROW_NUMBER()`, `PARTITION BY`, `AVG() OVER()`
- **CTEs**: Multi-step analysis with Common Table Expressions
- **Complex JOINs**: 4+ table joins for comprehensive analysis
- **Date Functions**: `YEAR()`, `CURDATE()` for temporal analysis
- **Aggregation**: `GROUP BY`, `HAVING` for business metrics

## 📋 Query Files
1. `01_salary_trends.sql` - Historical salary analysis
2. `02_department_analysis.sql` - Current department salary averages  
3. `03_salary_by_year_dept.sql` - Year-over-year department trends
4. `04_large_departments.sql` - Departments with 15K+ employees
5. `05_senior_manager.sql` - Longest-serving active manager
6. `06_salary_comparison.sql` - Employee vs department average comparison
7. `07_second_managers.sql` - Second manager in each department
