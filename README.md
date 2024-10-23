[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![Python Version](https://img.shields.io/badge/python-3.7-blue.svg)](https://www.python.org/downloads/release/python-370/) [![Made with VSCode](https://img.shields.io/badge/Made%20with-VSCode-1f425f.svg)](https://code.visualstudio.com/) [![Jupyter Notebook](https://img.shields.io/badge/Made%20with-Jupyter-blue.svg)](https://jupyter.org/) 

# Housing Trends Ontario 2010-2023

Housing Trends surrounding square footage, bedrooms/bathrooms, affordability of renters and first-time home-owners, most expensive cities for housing with their change over time, and the difference in housing cost for condiminiums, non-detached, semi-detached, and detached homes between 2010 to 2023.

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

