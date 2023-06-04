# Cab-Investment-Analysis
Go-to-Market(G2M) Analysis for 2 cab companies in 20 cities
* Created a tool to analyse cab business in major cities of the United States of America to identify the best cab company(s) to invest in and which cities are the most lucrative for business as well as the factors that help maximize profits.
* Examined over 350,000 transactions across 20 cities of the US
* Performed various EDAs on all the features of the cab business dataset as well as other factors that influence the business such weather and holidays

## Code and Resources used
**Python version:** 3.10.9

**Packages:** numpy, pandas, sklearn, matplotlib, seaborn

**Cab Business Datasets:** Data Glacier

**Weather Dataset:** https://www.visualcrossing.com/weather/weather-data-services#

**Holidays Dataset:** From several sources on Google search including https://www.timeanddate.com/holidays/us/2016?hol=25,  
https://www.employmentlawhandbook.com/employment-and-labor-laws/topics/leave-laws/holiday-leave/federal-state-holidays/

## Data Cleaning
* Datasets sourced (Cab_Data, City, Customer_ID and Transaction_ID) from Data Glacier were clean and used as is. Some observations with imcomplete information were dropped whiles merging the datasets.
* Holiday data was collected and prepared on Microsoft Excel. This allowed it to be prepared clean
* The weather data needed to be cleaned. All columns were dropped except the columns for city name, datetime and weather icon. 
* Other cleaning done include:
  - Merged all datasets into one
  - Made a new column for `Profit`
  - Made a new column for `age_group`
  - Made a new column for `month` of transaction
  - Made a new column for `year` of transaction
  - Made a new column for `Weekend`

## EDA
I performed univariate and multivariate analysis to gain insight into the data and to answer business questions such as:
  - What is the most patronised company?
  - The best cities to run the cab business
  - Profit and loss analysis
  - Average distance tavelled
  - Influence of weather and holidays
  
  ![Yearly Profit by Month](https://github.com/Ariyo347/Cab-Investment-Analysis/assets/113588909/9dd42562-9107-4a9b-9712-198b3cd598e8)
  
  ![Age group analysis](https://github.com/Ariyo347/Cab-Investment-Analysis/assets/113588909/1dd8c724-84e5-4855-b105-94ef130a050b)
  
  ![Average cost, price and profit by city](https://github.com/Ariyo347/Cab-Investment-Analysis/assets/113588909/09cd7dd0-5c3c-4cda-bee8-f976aad8381b)


