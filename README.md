[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![Python Version](https://img.shields.io/badge/python-3.7-blue.svg)](https://www.python.org/downloads/release/python-370/) [![Made with VSCode](https://img.shields.io/badge/Made%20with-VSCode-1f425f.svg)](https://code.visualstudio.com/) [![Jupyter Notebook](https://img.shields.io/badge/Made%20with-Jupyter-blue.svg)](https://jupyter.org/) 

# Housing Trends Ontario 2010-2023

Housing Trends surrounding square footage, bedrooms/bathrooms, affordability of renters vs. first-time homebuyers vs. repeat homebuyers, most expensive cities for housing with their change over time, and the difference in housing cost for condiminiums, non-detached, semi-detached, and detached homes between 2010 to 2023.

## Getting Started

### Installing

The first step is to install python on your computer. The recommended and most up to date version can be found using the link down below.

[Python](https://www.python.org/downloads/)

Once the python environment is installed, in order to run the code the next step is installing Microsoft Visual Studio Code (VScode). The link for VSCode can be found down below.

[Visual Studio Code](https://code.visualstudio.com/)

Find these under the extensions option inside Visual Studio Code:

  Install the Python extension and Jupyter extension for Visual Studio Code, which helps with features 
  like linting, debugging, Intellisense

### Usage

Run your Python scripts, or modify the platform code directly in the VSCode editor.

Use the terminal within VSCode to run the Python application.

Now, for the final step, run the code and if you find a bug or want to propose an improvement please create an issue.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Analysis and Conclusion

### How does square footage affect the listing price of residential properties in these three cities?

Cities in Focus: Guelph, Kitchener, and Windsor

![alt text](https://github.com/prom001-naf/Project1_Group5_DataBootCamp/blob/main/Data_Code_Analysis/Screenshot%202024-10-21%20210650.png?raw=true)

Major Findings: The correlation values between square footage and listing prices for all three cities are unexpectedly close to zero or negative, which suggests that square footage has a weak linear relationship with listing price in these cities. The correlation values are:

  •	Overall: 0.0039
  •	Guelph: -0.0231 (negative correlation)
  •	Kitchener: 0.0811 (weak positive correlation)
  •	Windsor: -0.0154 (negative correlation)

These weak correlations indicate that, in these cities, square footage alone does not have a significant impact on the listing price. The scatter plot visualizations for each city, along with the regression lines, support this finding by showing flat or nearly flat trends in the relationship between square footage and listing price.

  •	Guelph: The negative correlation in Guelph suggests that larger homes may be listed at slightly lower prices, 
    which could be due to factors like property condition, location, or market demand that override the effect of 
    square footage.
  o	Example: Homes with around 1,500 sq. ft. have listing prices ranging from $600,000 to $900,000, indicating no 
    clear pattern based on size alone.

  •	Kitchener: The weak positive correlation of 0.0811 suggests that while larger homes are priced slightly higher, 
    the relationship is not strong. This is further reflected in the scatter plot, where the data points are widely 
    spread around the regression line, showing minimal association between size and price.
  o	Example: Homes above 2,000 sq. ft. in Kitchener are priced between $700,000 and $900,000, but similarly sized 
    homes can have varying prices.

  •	Windsor: With a slightly negative correlation, square footage in Windsor has virtually no impact on listing 
    prices. This suggests that factors other than home size, such as neighborhood quality, market saturation, or 
    amenities, may play a more dominant role.
  o	Example: Homes with similar square footage vary widely in price, from $400,000 to $600,000, with no clear 
    relationship between size and price.

Conclusion:

  •	Kitchener shows a weak positive relationship between square footage and listing price, but the effect is minimal.
 
  •	In Guelph and Windsor, square footage shows no meaningful impact on listing price, with correlations even         
    suggesting slight negative relationships.
 
  •	These findings suggest that other factors, such as location, property type, or market conditions, are likely 
    playing a larger role in determining listing prices in these cities.

### What are the top three cities by number of bedrooms (including bathrooms)? How does the number of bedrooms (including bathrooms) affect the listing price of residential properties in these three cities?

Cities in Focus: Guelph, Toronto, and Kitchener

![alt text](https://github.com/prom001-naf/Project1_Group5_DataBootCamp/blob/main/Data_Code_Analysis/Screenshot%202024-10-21%20221537.png?raw=true)

Major Findings: The correlation values between number of bedrooms (including bathrooms) and listing price show similarly weak relationships. The correlation values are:
  
  •	Overall: 0.0010
  •	Guelph: -0.0144 (negative correlation)
  •	Toronto: 0.0558 (weak positive correlation)
  •	Kitchener: 0.0175 (weak positive correlation)

These values indicate that the number of bedrooms (including bathrooms) has little to no direct impact on listing prices in these cities. The box plot visualizations support this finding by showing a wide range of listing prices across different bedroom counts, with no clear pattern of increasing prices for homes with more bedrooms.

  •	Guelph: The negative correlation suggests that homes with more rooms may be priced slightly lower, which could be 
    due to market demand for smaller homes or other factors affecting price.
  o	Example: Homes with 3 rooms are listed between $600,000 and $900,000, with no clear price increase as room count 
    grows.
  
  •	Toronto: Despite being the largest market, the correlation between room counts and price is weak, with a 
    correlation of 0.0558. This suggests that in Toronto, factors such as neighborhood, proximity to amenities, and 
    property condition play a larger role in determining price than room count.
  o	Example: Homes with 4-5 rooms in Toronto range from $900,000 to over $1.5 million, indicating no consistent 
    relationship between room count and price.
  
  •	Kitchener: The correlation of 0.0175 is weak, indicating a minimal impact of room count on price. The box plot 
    shows overlapping price ranges across different room counts, further suggesting that the number of rooms is not a 
    strong driver of price.
  o	Example: Homes with 4 rooms in Kitchener have listing prices ranging from $600,000 to $900,000, with significant 
    overlap between homes with fewer or more rooms.

Conclusion:

  •	Toronto and Kitchener show a weak positive relationship between the number of rooms and listing price, but the 
    effect is minimal.

  •	Guelph shows a slightly negative correlation, indicating that homes with more rooms may be priced lower.

  •	Overall, the number of bedrooms (including bathrooms) has little to no impact on listing prices, with other 
    factors such as neighborhood or market conditions likely driving price variability.

#
## What is the Difference in Affordability for Renters vs. First-Time Homebuyers vs. Repeat Homebuyers?                                                   
#
![screenshot_employment](https://github.com/user-attachments/assets/035a03af-fb52-425a-a636-9d09a52f0e49)
#
### Key insights related to affordability:
### 1. First-time homebuyers:
•	The majority of households in this category are employed, with a very small portion being unemployed. This suggests that employment stability is likely crucial for first-time homeownership, which may imply 
  that owning a home for the first time is generally less affordable without a stable income.
  
•	The relatively small number of not employed first-time buyers indicates that this group may face higher barriers to homeownership due to financial pressures or the inability to secure a mortgage without employment.

•	Affordability challenge: First-time homebuyers likely face high upfront costs (down payments, closing fees) and must have sufficient income to qualify for home loans, making it less affordable for those without stable employment.

### 2.	Renters:
•	Renters show a much more balanced distribution between employed and not employed households. In fact, the number of not employed renters is significantly higher than in the other two groups, suggesting that renting might be a more affordable option for those without employment, compared to owning a home.

•	This balance suggests that renting offers more flexibility and lower entry costs (no down payment or long-term mortgage), which makes it more accessible for individuals who may not have a stable income or are between jobs.

•	Affordability challenge: Renters may still face rising rent costs, but the lack of upfront homeownership costs makes renting a more viable short-term option for individuals with less financial stability.

### 3.	Repeat homebuyers:
•	This group has the highest number of households overall, and the majority are employed. However, there is also a substantial number of not employed repeat homebuyers, which suggests that repeat homeownership may be more affordable even for households with lower or inconsistent income.

•	This may be due to factors such as accumulated home equity, access to better loan terms, or financial flexibility gained from previous homeownership.

•	Affordability advantage: Repeat homebuyers are likely more secure financially, allowing them to handle the ongoing costs of homeownership more easily compared to first-time buyers, even if they are not currently employed.

### Affordability Comparison:
•	Renters may experience greater affordability in the short term, especially for those not employed, due to lower upfront costs and flexibility. However, the long-term financial benefits of homeownership (e.g., building equity) are not available to them.
•	First-time homebuyers face the greatest affordability challenges, especially if not employed, due to the need for stable income and high upfront costs.
•	Repeat homebuyers appear to have greater affordability, even for those not employed, due to potential financial advantages like equity or better loan terms. Their experience and financial stability make homeownership more accessible to them compared to first-time buyers.

This comparison highlights how employment status and tenure play a significant role in determining affordability across different housing situations.
#
![screenshot_financial_needs](https://github.com/user-attachments/assets/6400de59-ed35-4fd8-9f8f-2371dcda9ecf)

### Key insights with cost-of-living affordability in mind:

### 1.	First-time homebuyers:
•	The financial needs of first-time homebuyers are generally moderate across most categories, with values ranging from 5,600 to 37,000.

•	While this group has significant financial demands (especially in the third category, reaching 37,000), the lower values in other categories suggest that first-time homeownership requires targeted but substantial financial resources, such as saving for down payments or covering initial homeownership costs.

•	Affordability Challenge: First-time buyers likely face more intense financial challenges in specific areas like upfront costs, but other expenses may be relatively lower than for repeat buyers.

### 2.	Renters:
•	Renters show consistently high financial needs across categories, particularly in the first and third categories where the needs rise above 83,000 and 94,000, respectively. This suggests that renters face a wide range of financial demands, which might relate to the cost of rent, utilities, or other living expenses.

•	The substantial financial needs imply that renting, while more accessible than homeownership, may still place a considerable financial burden on households, especially those with high ongoing costs.

•	Affordability Insight: Renting remains accessible in terms of lower upfront costs, but the consistently high financial demands might indicate challenges in long-term affordability due to recurring rent and other expenses.

### 3.	Repeat homebuyers:
•	Repeat homebuyers show the highest financial needs across all categories, particularly in the second and third categories, where the financial needs exceed 120,000 and 130,000.

•	These high financial needs suggest that repeat homeownership involves significant ongoing costs, which may include mortgage payments, property taxes, and maintenance, even though these homeowners often have higher financial security or equity.

•	Affordability Insight: While repeat homebuyers might have more financial stability and access to equity, the high financial demands in various categories suggest that the ongoing costs of homeownership can be substantial.

### Affordability Comparison:
•	Renters face consistently high financial needs, indicating that while renting may be more affordable in the short term, the ongoing costs can accumulate, especially for households with lower income.

•	First-time homebuyers show more targeted but significant financial needs, primarily related to upfront costs. This group must have a stable income or financial resources to cover these initial barriers to homeownership, but their ongoing costs may be slightly lower.

•	Repeat homebuyers experience the highest financial needs overall, likely due to ongoing costs of maintaining and managing owned properties. However, they may have financial advantages from equity or previous homeownership experience that can help mitigate these needs.

This comparison suggests that while renting may appear more affordable due to lower entry costs, it carries substantial recurring financial burdens. First-time homebuyers face high initial costs but may have lower ongoing financial demands than repeat homebuyers, who face the most significant financial needs overall, despite their potential financial stability.

## Research Questions: What are the most expensive cities in Ontario for housing and how have their average house values changed overtime?

Data Analysis:

The analysis aims to identify the most expensive cities in Ontario for housing and to examine how their average house values have changed over time. To achieve this, two visualizations were created: a tree map displaying the relative housing prices across different cities and a line chart illustrating the trend of average house values over specific time periods.

# Tree Map Analysis 

![alt text](https://github.com/prom001-naf/Project1_Group5_DataBootCamp/blob/main/newplot.png)
The tree map provides a visual representation of the housing market in Ontario, highlighting the most expensive cities based on average house prices. Each city is represented as a square, with the size and color shades corresponding to its average house values.

Key Observations:

o	Cities such as King, Markham, and Toronto stand out as the most expensive, occupying the largest areas within the tree map. This indicates that they have 
significantly higher average house prices compared to other cities.

o	King remains the most prominent city with approximately $1.6 million. Average house sold price, reflecting its status as a major urban center with high 
pricing for housing.

o	Cities like Markham and Toronto also show substantial average prices, indicating a competitive housing market in those areas.

o	Some neighborhoods like Brampton and Pickering, represented by lighter shades of blue, have shown an increase in average home sold values over time. This 
suggests a trend of rising home prices in these areas.

o	Cities like London, Woodstock, and Belleville are represented by red shades, indicating lower average home sold values compared to the top-tier 
neighborhoods.

o	This contrast highlights the significant price differences across various neighborhoods in Ontario.

# Line Chart Analysis 

![alt text](https://github.com/prom001-naf/Project1_Group5_DataBootCamp/blob/main/newplot1.png)
he line chart illustrates the changes in average house values in the top 3 cities over time, providing insights into trends and patterns.

Key Observations:

o	The line chart indicates a general upward trend in average house values across most cities from 2010 to 2023. This trend suggests a robust demand for 
housing in Ontario, particularly in urban areas.

o	King exhibits the most pronounced increase in average house values, particularly from 2020, which could correlate with economic growth and an influx of 
residents.

o	Around 2016-2017, there was a noticeable spike in home prices across all three cities.

o	Markham and Toronto have similar trends, with prices closely following each other, but both remain below King.

o	Notably, any periods of stagnation or decline in average house values can also be observed.

# Conclusion of Analysis

The combination of the tree map and line chart effectively illustrates that the most expensive cities in Ontario, particularly King, Markham, and Toronto have experienced significant increases in average house values over time. This upward trend emphasizes the ongoing housing market challenges in Ontario, driven by high demand, limited supply, and urbanization. Understanding these dynamics is crucial for potential buyers, investors, and policymakers as they navigate the complexities of the real estate market.






















