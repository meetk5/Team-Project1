# Team-Project1
This is our first team project. Our team "Data Super Warriors" aims to analyze the impact of Covid on Employment/UnEmployment in US. Our goal is uncover the employment patterns across various industries,demographics, races etc. We will try to establish the correlation between No. of Covid Cases, Vaccination rate and Unemployment. We will do county-wise analysis for New Jersey in particular. 


Impact of Covid on US Employment

Project Proposal:  To visualize the impact of Covid on Employment in the US.
Questions:
1.	How has Covid impacted employment in each industry of the job market in the US?
2.	How much has Covid impacted the unemployment rate in each county in the state of NJ?
3.	How has Covid impacted the employment rate of each age group, gender and race?
4.	What are the correlations between the unemployment rates of NJ vs. the US?
5.	Has the rate of Vaccinations impacted the rate of employment?
Data Sources:
1.	U.S. BUREAU OF LABOR STATISTICS:  https://www.bls.gov/ 
2.	New Jersey LAWD: https://nj.gov/labor/lpa/LMI_index.html
3.	Public APIs: https://www.bls.gov/developers/api_signature_v2.htm 
4.	DBs: https://www.bls.gov/data/ 
5.	Vaccination Data: https://data.cdc.gov/Vaccinations/COVID-19-Vaccinations-in-the-United-States-Jurisdi/unsk-b7fc 
6.	Data for Covid cases: https://github.com/nytimes/covid-19-data 

APIs:

Data Cleaning:
Effect_of_Covid_Unemployment_NJ_Data_Analysis.ipynb:  Gathered data from New Jersey LAWD website and created clean dataframe with each NJ county’s unemployment rates for every month starting from Jan 2019 to May 2021.











Reports:

Unemployment rates in NJ vs. number of vaccines administered:


![image](https://user-images.githubusercontent.com/84213057/126387253-d761a981-4915-4470-866f-76715d9f62f6.png)










•Data shows the monthly unemployment rates by County in the state of NJ

   o	Starting around the months of April unemployment peaked till June 2020 and started to drop in July 2020.
 
   o	The county with the highest unemployment rate during the peak was Atlantic County
 
   o	A significant outlier before Covid was Cape May County.

![image](https://user-images.githubusercontent.com/84213057/126387334-1a0b23c8-c0d8-419b-ac33-40b910adc1d1.png)
![image](https://user-images.githubusercontent.com/84213057/126387356-99f1b333-9efd-44a0-bc0d-befbcea4c873.png)


 
•	Data shows the unemployment rates for 2019 and 2020 by county in pie charts
 o	Pre-Covid, Cape May County had the highest unemployment rate at 6.9%
 o	Pre Covid, Hunderton County had the lowest unemployment rate at 2.6%
 o	2020, Atlantic County became the county with the highest unemployment rate changing from 4.9% to 17.8%
 o	Hunterton County remains the county with the lowest unemployment rate at 7.2%

![image](https://user-images.githubusercontent.com/84213057/126387394-67822df3-e9e0-4bed-a410-8ee80e8b1a22.png)
![image](https://user-images.githubusercontent.com/84213057/126387421-6a0955fc-a824-4425-9093-06d82f2f55c1.png)


•	Data shows the comparison of number of vaccines administered throughout NJ vs. the unemployment rates of NJ counties from December 2020 to July 2021
 o	There is a negative correlation between number of vaccines administered and unemployment rates.  As number of vaccines administered increased, the rate of unemployment throughout all counties decreased.  
 o	Vaccines administered started to plateau in June 2021 and similarly, unemployment rates also plateaued. 
 o	In conclusion, the data shows an increase of vaccines administered helped unemployment rates in NJ decline.
Team:
Brian Johnson (Bjohnson08021)
Meet (Meetk5) 
Byron (bpineda225) 
Vasav (Vasavdave)
Shreyas (ssrivastav0494) 
Megan (Mbutler22)

