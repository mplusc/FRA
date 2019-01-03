# Financial Risk Analyst Assessment

## Background
* Navy Federal is considering raising the interest rate on domestic automobile loans that we originate to 6%. Evaluate whether we should do this. Make sure your net income forecasts go out to Q4 2020, and you can assume zero origination and servicing costs in your calculations.  
* Here is additional information, if needed: 
 * Domestic automobile sales through Q4 2017 (see attached Excel file)
 * Macroeconomic data, with forecasts through Q4 2020 (see attached Excel file)  Average loan amount: $25,000
 * Portfolio loss rate per quarter: 1.00%
 * Current annual interest rate per loan: 5.00%
 * Average term: 3 years  Portfolio payoff rate per quarter: 1.50%
 * Percentage of domestic automobile sales Navy Federal finances: 3.00% 
* Also, based on previous analyses, increasing the interest rate to 6% would decrease the number of loans Navy Federal would originate by about 17%.  The payoff rate would also likely increase to about 2.50%.

## Data Cleaning
The data cleaning was done in a Jupyter notebook labeled as "FRA Assesment (cleaningdata)"

## Forecasting Model
My forecasting model for this assessment was done in a Jupyter notebook labeled as "FRA Assesment (model)".
This model was based on a few assumptions labeled in the background section above.
I used scikit-learn with a regression model to train and test the data for me to be able forescast the data through Q4 of 2020.
The model resulted in a R-Squared value of 0.318, which is low but when it comes to human behavior 0.3 is a fair level for the explained variance.

## Analysis
The majority of my analysis was done in the excel workbook labeled as "Lending Analytics - FRA Assessment - Data and Data Dictionary - Dec 2018.xlsx" in the resources folder.
* The "Data tab" was provided as well as the "Data Dictionary" tab.
* The "Forecasted Data" tab is where I input my forecast thorugh Q4 2020 which were obtained from the scikit-learn rgression model.
* Scenario 1 is the analysis of the current 5% interest rate.
* Scenario 2 is the analysis of the propsed 6% interest rate.
* The "Excel Data Analysis" tab is from the data analysis tool that excel has available.
* The "Comparison" tab has my charts & data analysis when taking into consideration the interest rate increase.
* The PowerPoint presentation has my final results, analysis summary and a brief descprtions of the technologies I used.




