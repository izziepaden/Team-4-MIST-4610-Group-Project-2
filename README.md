# Team-4-MIST-4610-Group-Project-2
MIST 4610, Team 4 Project #1
<br/>
<br/>

# Team Members 

1. Ashley Park [Ashley Park](https://github.com/ap86129) <br/>
2. Izzie Paden [Izzie Paden](https://github.com/izziepaden) <br/>
3. Carter Kowalski [Carter Kowalski](https://github.com/carterkowalski1) <br/>
4. Bharat Gupta [Bharat Gupta](https://github.com/BG57387) <br/>
<br/>

# **Description of dataset:**


Our dataset details the accidental drug-related deaths that happened from 2012-2022. We obtained our dataset through the US Data government website (https://catalog.data.gov/dataset). In our dataset, there are dimensions across different data types that describe the counts and other identifying factors related to the deaths. It includes dates, race, gender, and the many different drug types that caused the death, and where the death occurred by city, state, and county. These dimensions are also of datatype string. A couple more dimensions that are present in our dataset are the month and year that the offense occurred along with where the person was a resident from. These dimensions are of datatype string as well. The last dimensions include the date the death occurred on. This was of datatype date and time. Overall, our dataset varied across different dimensions that helped us analyze different patterns shown in the dataset of drug related accidental deaths in those years. 

<br/>

# **Question 1:**
In 2015-2020, what months tend to see increases in fentanyl related deaths? More specifically, are there any trends that can be seen such as days of the week that experience more fentanyl related deaths?

<br/>

Importance:
The question "In 2015-2020, what months tend to see increases in fentanyl-related deaths? More specifically, are there any trends that can be seen such as days of the week that experience more fentanyl-related deaths?" is insightful because it enables us to discern when fentanyl-related fatalities are most prevalent, facilitating a deeper understanding of temporal patterns in such incidents. By pinpointing specific months or days that consistently show higher numbers of deaths, healthcare providers, policymakers, and community organizations can tailor interventions more effectively. For instance, if data reveals that fentanyl-related deaths spike during certain months or on particular days of the week, targeted educational campaigns, enhanced medical services, and increased law enforcement efforts can be strategically deployed during these periods. The first part of the question allows us to identify broader trends across months, possibly correlating with seasonal changes or societal events, while the second part dives into weekly patterns, which might influence daily operational and staffing decisions in hospitals, treatment centers, and law enforcement agencies. Such granular insight is crucial for developing timely and context-specific responses to the opioid crisis, much like analyzing crime trends helps police departments optimize their patrol schedules and preventative measures.

<br/>
<img width="1125" alt="Screenshot 2024-04-26 at 4 03 54 PM" src="https://github.com/BG57387/Team-4-MIST-4610-Group-Project-2/assets/141380431/bd0a5afe-3bb1-4aef-93de-8eba4ec21534">
<br/>
Our graph presents a time series analysis of monthly deaths from fentanyl from 2015 through 2021. What stands out is the clear upward trend in fatalities over the years, with periodic fluctuations that indicate seasonal or other short-term variances. Unlike what one might expect, the pattern does not show a simple increase in warmer or colder months uniformly, which might suggest a complex interplay of various factors influencing fentanyl-related deaths. This rising trend underscores the growing impact of fentanyl on public health. The peaks and valleys observed within the data might correlate with specific events or policy changes, which warrants further investigation. This visualization sets the stage for a deeper dive into the causes behind these trends, similar to how examining drug overdoses by day can inform targeted law enforcement and community support strategies.

<br/>
<br/>
<img width="506" alt="Screenshot 2024-04-26 at 4 12 27 PM" src="https://github.com/BG57387/Team-4-MIST-4610-Group-Project-2/assets/141380431/1d00c692-2148-4b47-9129-ebed4198eb90">
<br/>
The graph portrays the counts of deaths from fentanyl by day of the week, offering a clear view of when these tragedies are most likely to be reported. A striking feature of the data is the notable increase on certain days, particularly toward the end of the week. This could suggest a pattern in which the use of fentanyl, or the reporting of its lethal outcomes, is more common as the week progresses, peaking around the weekend. This trend might reflect behavioral changes during different days of the week, such as increased recreational activities or substance use as people approach the weekend. Understanding these patterns is vital for planning emergency services and public health interventions. It could inform when to increase availability of resources such as emergency responders or overdose prevention programs. Just as the analysis of drug violations on different days provides insights for law enforcement, this pattern of fentanyl-related deaths can guide health service providers in optimizing their schedules and preparedness, potentially saving lives by aligning services with the times they are needed most.



<br/>
<br/>
<br/>

# **Question 2:**
Which counties have consistently experienced the highest or lowest numbers of heroin-related deaths over the past decade? More specifically, how does the impact of heroin-related deaths compare between males and females in different counties?

<br/>

Importance: 
The question "Which counties have consistently experienced the highest or lowest numbers of heroin-related deaths over the past decade? More specifically, how does the impact of heroin-related deaths compare between males and females in different counties?" is meaningful as it allows us to dissect both the geographical and gender-based dimensions of the heroin epidemic. By identifying counties with persistent high or low counts of heroin fatalities, this inquiry aids in recognizing regions where intervention and resources are most needed or where strategies might be particularly effective. The gender-specific aspect of the question can reveal disparities in the impact of the crisis, guiding tailored initiatives that address the unique needs of men and women. For instance, if one gender shows disproportionately higher death rates in certain counties, community outreach, treatment programs, and preventive strategies can be adjusted accordingly. Additionally, this analysis can inform local authorities about the effectiveness of their current efforts, enabling a data-driven approach to combating substance abuse. Like examining crime patterns assists in policing, scrutinizing these trends provides insights crucial for public health planning, resource allocation, and policy development.

<br/>
<img width="1265" alt="Screenshot 2024-04-26 at 4 28 06 PM" src="https://github.com/BG57387/Team-4-MIST-4610-Group-Project-2/assets/141380431/4cc144e6-67fb-44d4-aa86-6d25b294f839">
<br/>
This graph provides a year-over-year comparison of heroin-related deaths by county. We can observe significant variability in the data, with certain counties experiencing higher rates of fatalities than others. Some counties exhibit a sharp increase in deaths at certain points, possibly indicating a surge in heroin availability or a decrease in the quality of the drug leading to overdoses. Conversely, other counties show a decline or steadiness that might suggest the effectiveness of intervention programs or changes in drug use patterns. For instance, New Haven County shows a marked increase in deaths over time, which could trigger a closer examination of local factors contributing to this trend. By analyzing these fluctuations, public health officials can prioritize resources and target strategies to areas with the most critical needs. 
<br/>
<br/>

<img width="1245" alt="Screenshot 2024-04-26 at 4 29 42 PM" src="https://github.com/BG57387/Team-4-MIST-4610-Group-Project-2/assets/141380431/ff75efff-1b5e-4f58-a99a-2f88c7cc08bd">
<br/>
The graph delineates the total count of deaths by heroin, segmented by gender across various counties. The stark contrast in the numbers between males and females across each county is immediately apparent, with male deaths overwhelmingly exceeding those of females in every displayed region. This gender disparity could reflect differences in substance abuse patterns and risk behaviors between men and women, suggesting the need for gender-specific approaches in public health and law enforcement strategies. For instance, the graph shows that in New Haven County, the count for males is considerably higher than for females, pointing towards a potentially different impact of heroin use or availability in this gender group. 


<br/>
<br/>
<br/>

# **Manipulations applied to the data set for analysis**
We did not have to modify our data in any way. Our data has quantifiable data that can be measured and adheres to the standard of being meaningful, interpretable, and sigfncicant. It is, is laid out in a way that is free from duplicates, irrelevant entries, redundancy, inaccuracies, or any elements of poor quality.

<br/>
<br/>


# **Tableau packaged workbook**
The packaged workbook can be found at the top of this repository.
