# Kickstarting with Excel

## Overview of Project

### Purpose
The concept behind this project is to evaluate Kickstarter data, and determine how different campaigns fared in relation to competing campaigns. Analyzing data provided including category, country, launch dates and funding goals/outcomes provides us with insightful guidance for future campaigns.  The purpose of this exercise, specifically, is to evaluate the outcomes based on launch date and goals that will provide our client (Louise) with insightful data for running successful subsequent fundraising campaigns.

## Analysis and Challenges

### Analysis of Theater Outcomes Based on Launch Date
This analysis demonstrates a comparison of outcomes (successful, failed, canceled) by month of year and references a pivot table which had been filtered on critical data points including: Parent Category, Date Created Conversion (by Month), Outcomes and a Count of Campaign names.

![https://github.com/havgirl/Kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png](https://github.com/havgirl/Kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)


### Analysis of Outcomes Based on Goals
This analysis provides a percentage rate of success/failure at each incremental goal threshold. This was calculated by creating a table utilizing **countifs()** formulas to hone in on goal threshold, outcome and subcategory criteria.  Additionally **sum()** and percent formulas were used.

![https://github.com/havgirl/Kickstarter-analysis/blob/main/Outcomes_vs_Goals.png](https://github.com/havgirl/Kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)


### Challenges and Difficulties Encountered

- Accurately representing the data in visual graphs that would meet our clients expectations required additional virtual learning to depict canceled projects using a gap in place of a zero
- The Countifs formula required practice, therefore a lesson refresh was needed


## Results

### Theater Outcomes by Launch Date - Conclusions
- Campaigns created in May had the highest volume of successful theater outcomes
- The least amount of campaigns were kickstarted in December, which also yielded the hightest percentage rate of failures 
 
### Outcomes Based on Goals - Conclusion
- Campaigns that had a goal range less than $5,000 were the most successful, with a 76% success rate for projects less that $1,000 and 73% for projects with a goal between $1,000 and $4,999.

### Limitations of this dataset
Additional information could provide us with more context on why campaigns were successful and would assist in the analysis and recommendation process.  Examples include:
- Methods for advertising and circulating the campaigns were unknown
- The use of gifts to donors who pledged or exceeded a $ threshold were unknown
- The location within each country was unknown (city vs country, for example, could yield different results)

### Recommendations for additional tables or graphs
- [ ] Trend graph depicting outcome by year filtered by category
- [ ] Bar graph showing outcome by category and/or by country
- [ ] Table/graph demonstrating average donation by category

    