# Cleaning_Energy_Supply_and_GDP_Dataset
A Data Science Project




In this project, I cleaned a dataset that included a list of indicators of energy supply and reneweable electricity production from the United Nations. While cleaning, I excluded the footer and the header information and the first two unncessary columns, changed the column labels, converted energy supply to gigajoules, renamed some countries with missing values as NaN and removed numbers or parenthesis from some countries' names. Next, I loaded another file with GDP data of countries from the World Bank website from 1960 to 2015 and cleaned it a little bit. After this, I loaded another file which ranked countries based on their journal contributions in energy engineering and power technology. After cleaning all of these datasets, I merged the three datasets to create a dataframe showing the top 15 countries with greatest journal contributions, along with their corresponding GDP (from 2006-2015), and their corresponding energy supply and reneweable electricity production. Also, I wrote code to perform many other functions. For example, I wrote code to calculate the average GDP over the last 10 years for each country, to create a column that estimates the population using energy supply and energy supply per capita, and to create a column that estimates the number of vitable documents per person.
