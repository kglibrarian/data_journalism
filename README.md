## Data Journalism with D3.js

The code in this repository uses HTML, JavaScript, and D3.JS to visualize U.S. Census Bureau and the Behavioral Risk Factor Surveillance System data using scatter plot charts. These charts illustrate the current trends shaping people's lives, and include interactive elements to help readers understand the findings.

The data set included with the repository is based on 2014 ACS 1-year estimates. The current data set inculdes data on rates of income, obesity, poverty, etc. by state. MOE stands for "margin of error."

The main scatter plot show two of the data variables such as `Healthcare vs. Poverty` or `Smokers vs. Age`. Using the D3 technique, the scatter plot represents each state with circle elements. The graphic is coded in the `app.js` file of the directory, and the data is from `data.csv`. 
The axes and labels are to the left and bottom of the chart. 

Note: You'll need to use `python -m http.server` to run the visualization. This will host the page at `localhost:8000` in your web browser.

Data Boot Camp © 2018. All Rights Reserved.
