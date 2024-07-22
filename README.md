# pandas-challenge

**Module 4 Challenge - Pandas**

**School District Performance Analysis**

## Overview

This project aims to analyze the performance metrics of a school district, providing insights into various factors impacting student achievement. By examining district-wide averages, school-specific data, and performance across different spending ranges, school sizes, and school types, we identify key trends and draw meaningful conclusions.

## Project Structure

The project is organized as follows:

- **Resources/**: Contains the original CSV files for schools and students data.
- **Summary Results/**: Contains the generated summary CSV files.
- **school_data_analysis.ipynb**: Jupyter notebook with the code for data analysis.
- **README.md**: Project documentation (this file).

## Usage

Open the Jupyter notebook and run the cells to perform the analysis.

1. **Load Data**: The notebook loads the school data and student data from CSV files.
2. **Clean Data**: It performs data cleaning operations to prepare the data for analysis.
3. **District Summary**: Provides a high-level overview of the district's performance.
4. **School Summary**: Offers a detailed breakdown of each school's performance.
5. **Top Performing Schools**: Lists the top 5 performing schools based on overall passing rate.
6. **Bottom Performing Schools**: Lists the bottom 5 performing schools based on overall passing rate.
7. **Math and Reading Scores by Grade**: Shows the average math and reading scores for each grade level.
8. **Scores by School Spending**: Analyzes performance based on the per-student budget.
9. **Scores by School Size**: Analyzes performance based on school size.
10. **Scores by School Type**: Analyzes performance based on the type of school (Charter or District).

## Output

The notebook will generate various tables and visualizations that provide insights into school performance. Below are some examples of the outputs you can expect:

### District Summary

- **Total Schools**: 15
- **Total Students**: 39,170
- **Total Budget**: $24,649,428.00
- **Average Math Score**: 79.0
- **Average Reading Score**: 81.9
- **% Passing Math**: 75.0%
- **% Passing Reading**: 85.8%
- **Overall Passing Rate**: 80.4%

### School Summary

- Each school's performance metrics such as average scores and passing percentages.

### Top Performing Schools

- Lists the top 5 schools based on the overall passing rate.

### Bottom Performing Schools

- Lists the bottom 5 schools based on the overall passing rate.

### Scores by Grade

- Average scores for math and reading for each grade level.

### Scores by Spending, Size, and Type

- Various insights based on spending per student, school size, and school type.

## Generated Summary Files

The following summary files are generated and saved in the **Summary Results** folder:

- **district_summary.csv**: Overall district performance metrics.
- **per_school_summary.csv**: Key metrics for each school.
- **top_schools.csv**: Top-performing schools based on overall passing percentage.
- **bottom_schools.csv**: Lowest-performing schools based on overall passing percentage.
- **math_scores_by_grade.csv**: Average math scores by grade level for each school.
- **reading_scores_by_grade.csv**: Average reading scores by grade level for each school.
- **spending_summary.csv**: School performance based on spending ranges.
- **size_summary.csv**: School performance based on school size.
- **type_summary.csv**: School performance based on school type.

## Analysis and Findings

The analysis provided comprehensive insights into the factors influencing student achievement. Key findings include:

### Spending and Performance

1. Higher spending per student correlates with higher math and reading scores and better passing rates.
2. Smaller schools (under 1,000 students) outperform larger ones, suggesting smaller sizes enhance learning.
