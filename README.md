# Impact of COVID-19 on Unemployment in US

![image](https://user-images.githubusercontent.com/83404547/126716068-dc89b679-0ec7-4e18-89fd-241abe201f0c.png)


# Project Proposal: 

This project aims to analyze the impact of COVID-19 on Unemployment in US. Our goal is to uncover the unemployment patterns across various industries, demographics, races etc. We established the correlation between number of Covid Cases, Vaccination rate and unemployment. We conclude the analysis with the data from the state of New Jersey and its counties, while correlating it with vaccination rate. 

# Questions:
1.	How has Covid impacted the employment in US industries?
2.	What is the correlation between number of Covid Cases and Unemployment?
3. How has Covid impacted the unemployment amongst different races?
4.	Comparative analysis on Unemployment situtaion within Tri-State Area.
5.	How much has Covid impacted the unemployment across NJ state and counties? 
6.	Has the rate of Vaccinations impacted the rate of unemployment in US ?


# Data Sources:
1.	U.S. BUREAU OF LABOR STATISTICS:  https://www.bls.gov/ 
2.	New Jersey LAWD: https://nj.gov/labor/lpa/LMI_index.html
3.	Public APIs: https://www.bls.gov/developers/api_signature_v2.htm 
4.	DBs: https://www.bls.gov/data/ 
5.	Vaccination Data: https://data.cdc.gov/Vaccinations/COVID-19-Vaccinations-in-the-United-States-Jurisdi/unsk-b7fc 
6.	Data for Covid cases: https://github.com/nytimes/covid-19-data 



# Data Cleaning:
Effect_of_Covid_Unemployment_NJ_Data_Analysis.ipynb:  Gathered data from New Jersey LAWD website and created clean dataframe with each NJ county’s unemployment rates for every month starting from Jan 2019 to May 2021.



# Analysing Various Industries across U.S.

We begin with analyzing Unemployment in various industries in US. As we analyse each industry, we realize that industries such as Food & Drink Services, Education & Health Services, Government services, Goods Producing Industry, Information Industry etc. was negatively impacted during March-April 2020 at the advent of pandemic. 

<img width="510" alt="image" src="https://user-images.githubusercontent.com/83404547/126714624-5e538ef8-24c3-4c26-afb9-0d1ef92e929d.png">

![image](https://user-images.githubusercontent.com/83404547/126715446-ab3163eb-ed46-4104-8551-f7017de99694.png)

Analysis was extennded to compare various industries and to idenntify Food & Hospitality industries being the worst hit while Information Industry and Government Services were least impacted. Education & Health Services remained least imapcted and managed to survive the recession.

![image](https://user-images.githubusercontent.com/65046405/126682434-3fd1f14b-7b45-4b32-a4ac-3726ba54c3d6.png)

Followed by industry-level analysis, we did the month-wise analysis from Jan-2020 to June-2021 comparing the Number of Covid Cases with Unemployment in US.

![image](https://user-images.githubusercontent.com/65046405/126682932-37d7d638-3fcf-4da0-9b4c-ed6bd13c033e.png)

As seen from the double line grapth, the unemployment was at it's peak in April-2020 but it slowly came down and has recovered considerably. The number of Covid Cases on the other hand began in Jan-2020 and have considerably risen till May-2021 before they gradually started falling in June-2021. 

# Correlation between COVID cases and Unemployment 

To further strengthen our hypothesis, we created a Scatter plot and established Linear Regression between the two variables. 

![image](https://user-images.githubusercontent.com/65046405/126683728-777809de-6a8f-40d4-a00d-51f26b1e1c99.png)

As can be seen from the scatter plot, there's a very weak relation between the Number of Covid Cases and Unemployment. Also, they are negatively correlated. From the r-value (-0.34) and p-value (0.17), it can be concluded that the correlation is not statically significant.
Therefore, although Employment was hit the most in April-2020 when Covid started, it recovered considerably irrespective of the number of Covid Cases as the industries learnt their ways to combat the problem.




Reports:


-------------------------------------------------------------------------------------------
# Analysing Impact of Vaccination on Employment

Details for this analysis can be found in the jupyter notebook – “Covid-19 Vaccination administrated and its impact on US Unemployment-checkpoint.ipynb”
This part of the team project examined if Covid vaccinations administered had a relationship with the reduction of unemployment numbers in the US. The number of Covid vaccinations administered was used for this study and not the amount delivered. The reason for using the administered vaccinations numbers is even though there were more vaccines delivered if they were not administered then those had no impact. This data was sourced from the Center for Disease Control.
A common theme we have heard from our government and health officials almost on a regular basis about Covid-19 is that "getting shots in the arms" would be a key to getting back to normalcy, reducing transmission rate, reducing death rates, and getting our economy back on track. Simply getting vaccinated alone would not end the pandemic but would be one of the measures to reduce the impact it has had on our lives and economy.
Other measures clearly played a more immediate role in improving the unemployment rates since April 2020 such as the three rounds of economic stimulus checks, employees working remotely instead of being laid off, companies/businesses adapting their business models and other things going beyond this study. If we look at the unemployment rates in the US in April when our unemployment rate peaked at over 14, you will a drastic reduction of unemployment rate to around 8 by August. Since data for vaccination administered were not available until 2020 other factors played a key role in the reduction of unemployment.
This screen grab gives a bit of information concerning the vaccination file from the Center for Disease Control used for this project and the cleanup involved.

![image](https://user-images.githubusercontent.com/84112237/126553548-d66807c5-27f1-484a-9b05-89484c730587.png)

 
The graph gives us a big picture view of the unemployment rates in the US.
![image](https://user-images.githubusercontent.com/84112237/126553595-7e0f4cc1-fea3-4d9a-8660-eda8c492d2ae.png)

 
The vaccination file remediated earlier was used in conjunction with the unemployment file to produce the graph below.
For this graph subplots were used to set two different graphs on one plot. The vaccination data had to be scaled down to 10 millions to work with the unemployment figures which ranged from roughly 4 to 14 percent. Vaccination data is pictured in blue. Unemployment rate was colored in red and not scaled down. Two different x-axis and two different y-axis were used for this with vaccination data available from December 2020 - July 2021 and unemployment data available from January 2020 - June 2021. In the next graph we will zone in on the more macro view from December 2020 - June 2021.

![image](https://user-images.githubusercontent.com/84112237/126553641-31556c00-5c0f-4ded-8502-8339df70af52.png)
  
A closer look at unemployment rate versus vaccination rates for December 2020 - June 2021. The graph below represents a closer look at unemployment rate versus vaccinations administered. In this case only data from December 2020 through June 2021 was used to give us a magnified view of a crucial period when vaccinations started being administered and how unemployment was affected. On the upper right-hand side I added in annotation to give a sense of what the number of jobs grew/reduced for each month as small percentage in changes to unemployment rates might not seem like much. Also, the annotation above the vaccines (x-axis) lets you know which month it is associated with. For example, the difference in number of jobs added between January 21 and March 2021 was approximately 1.12 million additions and difference between April 2021 - May 2021 was an addition of approximately 940K. So, although these may look like insignificant reductions in unemployment rate the difference can account for a lot of job additions. In some cases, the difference between December 2020 and January 2021 lost about 700K jobs but shows a reduction of unemployment rate. Part of this may be employees no longer being considered as unemployeed because of a voluntary decision not to return to work. The plot shows in general that as vaccinations increased so did the rate of unemployment. There was a slight rate of unemployment increasing from 6.0 to 6.1 percent between March 2021 and April 2021 even though the jobs increased by approximately 800K. From May 2021 to June 2021 there was an increase of about 580K jobs, but the unemployment rate jumped from 5.8 to 5.9 percent.

![image](https://user-images.githubusercontent.com/84112237/126553708-8aa3566f-88db-4a2a-bd14-a7772564a06d.png)

 
Create the scatter plot and compute the Pearson correlation coefficient between "Unemployment Rates" and "Vaccines Administered"
When we created the scatter plot and computed the Pearson correlation coefficient between "Unemployment Rates" and "Vaccines Administered" it produced a negative or inverse correlation of -86 which is a strong indicator of a relationship between those two variables. That negative correlation describes a relationship between two variables that move in opposing directions. Or you can think of this as one variable increased (vaccines administered), then the value of the other variable (unemployment rates) decreased. In this case, as more Covid vaccinations were administered there was a decrease in the unemployment rate.
Remember correlation does not imply causality even if there is a strong correlation between the two variables! The correlation coefficient simply represents the degree of association between two sets of measurements.

![image](https://user-images.githubusercontent.com/84112237/126553751-0cd7f8cd-95bf-4c6b-9a82-f569fa92a1df.png)

 
Calculate and show the linear regression equation and line to plot.
The mathematical formula is composed of a response variable (y), in this case the unemployment rate, and the predictor variable (x) or the vaccinations administered. The formula predicts in this case unemployment rate, when vaccinations administered values are known.

![image](https://user-images.githubusercontent.com/84112237/126553801-5104ef5c-56cb-4f61-b051-ec0b83cf0094.png)

 
Simply put an R-squared indicates a measure of how close the data is to the fitted regression line. R-squared is the square of the Pearson's correlation coefficient. In the above graph, Pearson's correlation coefficient was calculated as (-.86) so the expected R-squared value would be .7496 approximately.
In general, higher R-squared values represent smaller differences between the observed and fitted values. In this analysis the R-squared was 0.75 indicating a fairly strong relationship. The p-value obtained here is 0.0120998 which is well below the standard <.05. If we obtained a large p-value, it would suggest that changes in the predictor (vaccinations administered) are not associated with changes in the response (unemployment rate). However, in this case the small p-value equates to changes in the predictor value (vaccinations administered) are related to changes in the response variable (unemployment rates).

At least mathematically there looks to be a statistically significant relationship between the number of vaccinations administered and unemployment rates.

-------------------------------------------------------------------------------------------
# Unemployment Amongst Different Races

In 2020, 18.9% of the Hispanic population in the United States were unemployed, the highest unemployment rate of any ethnicity while the national unemployment rate stood at 8.8 percent.

<img width="461" alt="image" src="https://user-images.githubusercontent.com/83404547/126705840-8a09d025-efc6-497d-b3c3-b8a2848ef1d2.png">

**Statewise Unemployment Scenario**

<img width="597" alt="image" src="https://user-images.githubusercontent.com/83404547/126705412-a589d28a-f5d9-4dc0-b12b-94f3614b2bb3.png">

**Unemployment in NJ 2020**

<img width="935" alt="image" src="https://user-images.githubusercontent.com/83404547/126703934-08a34375-e224-438a-b5c5-12f6d52ce136.png">

**Trends among Asian Workers**

Asian workers have seen uncharacteristically high unemployment rates throughout the pandemic, with their overall rate still just above 5% in June 2021.
During 2020, Asian workers saw the highest unemployment rates in Nevada (16.9%), and Hawaii (12.1%).

District of Columbia state saw the lowest Asian unemployment rate among the available states, at 4.0%.This rate was also below that of white workers in that state, whose unemployment rate was 4.1%.

In the state of New jersey as well the rate for Asian population was lowest among other races at 8.1% well below average rate of the state (10.5%).

**Consistent Unemployment Gap betwee Black and White Population**

<img width="390" alt="image" src="https://user-images.githubusercontent.com/83404547/126704400-e2bd2ae6-6326-4c64-8e06-3476ddecbdcc.png"> 

African-American Workers workers have seen uncharacteristically high unemployment rates throughout the pandemic, with their overall rate still above 9% in June 2021. During 2020, black workers faced unemployment rates over 10% in 23 states out of 41 for which unemployment data for Black workers was available.
Unemployment rates were highest for Black workers in Michigan (19.1%), Nevada (18.5%) and Pennsylvania (17.2%).
Among states with available data, the unemployment rate for Black workers was lowest in Alaska, with a rate of 5.2%. 

In the state of New jersey Black workers were more likely to get unemployed compared to other races with highest unemployment ratio of 13.4% above the average rate of 10.5% in NJ state.


**Widening Gap of Unemployment between White and Hispanic Work Group**

<img width="462" alt="image" src="https://user-images.githubusercontent.com/83404547/126704655-c8a30db8-bf40-4394-8ebd-874fff196bb6.png">

The overall unemployment rate for Hispanic workers was the highest (18.9%) amongst the other races during the pandemic of 2020. Yet it fell below that of Black workers’ to 7.4% in June 2021, still 3.1 percentage points above the pre-pandemic economic peak.

Hispanic workers in Massachusetts faced the highest unemployment rate of all groups measured, at 15.3%, followed relatively closely behind by Hispanic workers in Rhode Island who faced a 15.2% unemployment rate, and Hispanic Nevadans at 15.2%.  Hispanics in NJ also reported above 10% unemployment rate at 11.5%.

Hispanic workers in Kentucky saw the lowest unemployment rates in our data at 4.7%, followed by Hispanic Arkansas at 4.8%.

**Trends among white workers**

In June 2021, the white unemployment rate was 5.2%, still up 1.3% points relative to what we now recognize was the peak (3.9%) of the previous economic recovery in March 2020. During the pandemic of 2020, average white unemployment rate was at 6.6% with only 2 states being above 10% unemployment rate that is Hawaii and Nevada. Hawaii facing the highest rates, at 11.8%, likely due to the significant blow the pandemic dealt to the tourism and hospitality industries. 


**Unemployment Rates Recovering in Junne 2021**

<img width="716" alt="image" src="https://user-images.githubusercontent.com/83404547/126705273-cb569c3a-76c5-45c7-94c3-5a4b7a136253.png">


-------------------------------------------------------------------------------------------

# Tri-State Unemployment Analysis

Between Jan’19 to March’20, unemployment rates were within the 3.0 to 4.0 range with Pennsylvania and New York relatively even in their unemployment rates while New Jersey remained slightly lower, ranging between the 3.5 to 3.6 mark. 

<img width="300" alt="image" src="https://user-images.githubusercontent.com/83404547/126832838-06ec13d0-0aac-4057-9cd6-816fd459f01b.png">

Once the pandemic hit in March of 2020, both Pennsylvania and New Jersey unemployment  trippled in their rates to the 15 to 16 point range, leaving New York remaining at a lower rate of 3.9. It was not until May of 2020 that we were able to see a significant impact with New York and Pennsylvania’s unemployment rate rising to the 16.0 range.

<img width="327" alt="image" src="https://user-images.githubusercontent.com/83404547/126832941-c6b8c3c0-68a2-49c1-afb1-c4932dea3346.png">

New Jersey had a slightly better recovery starting in September of 2020 dropping just below the 10.0 range.
New York had a massive decrease by November and December of 2020, rising again in January of 2021 to the 10.0 range, only to gradually decrease within the 8 to 7 point range.

<img width="327" alt="image" src="https://user-images.githubusercontent.com/83404547/126833019-9a56d4d7-4982-4c71-89cf-766aa2caec5f.png">

•	The New York unemployment rate remains the highest of each state throughout the 3 years.

<img width="327" alt="image" src="https://user-images.githubusercontent.com/83404547/126833053-d1c408e6-2ef0-4038-b8f4-52a6fbea2f0b.png">

•	Pennslyvania and New York unemployment rates remain slightly higher than New Jersey post- recovery 2021 thus far.



-------------------------------------------------------------------------------------------
# Unemployment Across NJ State and Counties


<img width="317" alt="image" src="https://user-images.githubusercontent.com/83404547/126707432-59dd332d-9cc7-45ba-8941-e4e2313e0fbc.png">



•Data shows the monthly unemployment rates by County in the state of NJ

   o	Starting around the months of April unemployment peaked till June 2020 and started to drop in July 2020.
 
   o	The county with the highest unemployment rate during the peak was Atlantic County
 
   o	A significant outlier before Covid was Cape May County.
   
   
<img width="419" alt="image" src="https://user-images.githubusercontent.com/83404547/126833210-12279452-a14b-4794-9162-b679e01ad72f.png">
 
Data above shows the unemployment rates for 2019 and 2020 by county.
   - Pre-Covid, Cape May County had the highest unemployment rate at 6.9%
   - Pre Covid, Hunterdon County had the lowest unemployment rate at 2.6%
   - During 2020, Atlantic County became the county with the highest unemployment rate from 4.9% to 17.8%
   - Hunterdon County remains the county with the lowest unemployment rate at 7.2%
     
![image](https://user-images.githubusercontent.com/84213057/126577891-2b9e83a1-47fd-4ef7-a23b-c52a81ed4ccc.png)

Number of vaccines administered throughout NJ vs. the unemployment rates of NJ counties between December 2020 and July 2021, shows negative correlation between the two.  But as number of vaccines administered increased, the rate of unemployment throughout all counties decreased.

   - Vaccines administered started to plateau in June 2021 and similarly, unemployment rates also plateaued. 
   - An increase in number of vaccines administered corresponded with a decrease in unemployment rates in NJ.
 
 
 # Libraries:
        pip install pandas
        pip install geopandas
 

-------------------------------------------------------------------------------------------------------------------------

-------------------------------------------------------------------------------------------------------------------------
# Team:

https://github.com/meetk5)

        Meet K Kaur Sahni (https://github.com/meetk5) 
        Byron Pineda (https://github.com/byronpineda225)
        Vasav Dave (https://github.com/vasavdave)
        Megan Butler (https://github.com/Mbutler22)
        Brian Johnson (https://github.com/Bjohnson08021)



