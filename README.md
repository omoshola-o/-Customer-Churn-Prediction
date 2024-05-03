​External Indicators, such as CPI(CUUR0000SA0R), fed-rates(DFF), housing(HOUST), prime(MPRIME), unemployment-rates(UNRATE) from https://fred.stlouisfed.org (https://fred.stlouisfed.org/) were utilized in this analysis,
the approach to join these indicators to our data frame is as follows:     
⁃    Retrieve and import these indicators from the source in form of a CSV file     
⁃    Utilize the start and end date by first of all getting the indicator value as of the start and then getting the difference between that value and the value as of the end/current date.     
⁃    This difference is what is defined as the change in the external indicator, this way, we can get a dynamic change from the customer start date, to the c ustomer end-date/current date.
