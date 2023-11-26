# Analysis of Indian Start-ups Funding (2018-2021)
 
# Business Understanding
 
# Objective
The primary objective of this analysis is to understand the dynamics of funding received by Indian start-ups and to uncover insights into the distribution, trends, and correlations among sectors, funding stages, and geographical locations.
 
# Dataset Overview
The dataset comprises details of various start-ups, their funding amounts, funding stages, sectors, founding years, headquarters, and investors' information. This comprehensive dataset allows us to perform an in-depth analysis of the funding landscape and its implications for different sectors and stages of growth.
 
# Methodology
We'll employ data visualization techniques, statistical analyses, and exploratory data analysis (EDA) to extract meaningful insights from the dataset. By examining funding trends, sector-wise funding distributions, geographical impact, and stage-specific funding patterns, we aim to provide a comprehensive view of the Indian start-up ecosystem's financial landscape.
 
## Alternative Hypotheses
 
1)	There is a positive trend of increasing funding on a yearly basis in the Indian startup ecosystem.
2)	Certain sectors will emerge as dominant in the top 10, based on their funding amounts.
3)	The sector with the highest number of startups among the top 10 will also receive the highest funding.
4)	Specific sectors will show a higher concentration of startups compared to others.
5)	Startups in certain sectors will tend to receive higher amounts of funding due to sector-specific characteristics.
6)	Startup headquarters located in specific regions will receive higher funding than others.
7)	The geographic location of a startup's headquarters significantly influences its funding amount.
8)	Certain locations will have a higher density of startups compared to others.
9)	The stage of a startup will impact the amount of funding it receives.
10)	Certain stages in a startup's development will be associated with higher levels of funding compared to others.

## Basic Questions
 Some basic questions that could be answered at the end of the analysis:
1)	Is there a trend of increasing funding on a yearly basis?
2)	What are the top 10 sectors based on funding amounts?
3)	Which sector among the top 10 received the highest funding?
4)	Which sectors have the highest number of startups?
5)	How does the sector influence the amount of funding a startup receives?
6)	Which startup headquarters locations receive the highest funding?
7)	How does the location of a startup's headquarters impact its funding?
8)	Which locations have the highest number of startups?
9)	Does the stage of a startup impact the amount of funding it receives?
10)	Which stages are associated with higher levels of funding? 
## what needed to be done
 
1. Year of Funding Information:
 
Display the distribution or counts of funding across different years.
Perhaps create a visual representation like a line chart or a bar chart to show funding trends over the years.
 
2. Location Information:
 
Present details about the locations or headquarters of the startups.
Utilize a map or a bar chart to show funding amounts or counts by location.
 
3. Stage of Development Information:
 
Showcase the stages at which startups received funding.
Useing a bar chart or pie chart to illustrate the distribution of funding across various stages of development.
 
4. Sector of Operation Information:
 
Provideing insights into the sectors in which the startups operate.
Present a pie chart, bar chart, or any visual representation to display the distribution or amounts of funding across different sectors.
 
5. Amount of Funding Information:
 
High lighting the funding amounts or ranges received by startups.
Utilize a bar chart, histogram, or other visualizations to represent the distribution of funding amounts.
 
 
 Data-Related Issues:
 
1. Inconsistent Column Names:
 
Data18's column names differ from other datasets, causing incongruity.
Solution: Rename Data18's column names to align with other datasets.
 
2. Unnecessary Column:
 
Data20 includes an unnecessary 'unnamed: 9' column.
Solution: Remove the 'unnamed: 9' column from Data20.
 
3. Missing Columns in Data18:
 
Data18 lacks columns for founders, investors, and the year founded.
Solution: Add missing columns with null values for founders, investors, and the year founded in Data18.
 
4. 'Amount' Column Format:
 
The 'amount' column in all datasets contains currency symbols, commas, and is stored as a string.
Solution: Convert 'amount' values in all datasets to dollars as floating-point numbers.
 
5. Null Values:
 
Null values are present in the 'founded', 'headquarter', 'sector', and 'stage' columns.
Solution: Replace null values in the 'amount' column using the mean or median.
 
6. 'Headquarter' Column Variations:
 
Data18's 'headquarter' column contains additional information compared to other datasets.
Solution: Modify Data18's 'headquarter' by separating values with commas and keeping only the first word.
 
7. Inconsistent 'Sector' Values:
 
'Sector' values vary among all datasets, making standardization necessary.
Solution: Standardize sector values by merging similar categories (e.g., 'ecommerce' and 'e-commerce platforms' into 'e-commerce').
 
8. Data Type Inconsistencies:
 
Most data types are represented as objects, lacking uniformity.
Solution: Adjust the data types of each column accordingly for consistency and accuracy.
 
## Conclution
 
Based on our ANOVA Test analysis of the hypothesis, we failed to reject the null hypothesis. This suggests that there isn't a significant difference in funding amounts across various sectors.