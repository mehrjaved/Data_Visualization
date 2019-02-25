# Final Project 

## Part 1: Project Outline 

### Project Summary: 
The reported cases of Sexually Transmitted Diseases (STDs) in the US reached an all time high in 2017. This project will depict the growth of STD prevalence graphically, before providing preventative measures individuals can engage in to tackle this growth. 

#### Story Arc: 

1. Describing the rising rates of STD prevalence in the United States 
2. Background explaining what STDs are, and why they are a concern
3. Exploring potential reasons for this rise in STD prevalence 
4. Existing policies to combat growth in STD prevalence 
5. Alternative solutions to prevent the spread of STDs

### The Data 

The primary source of data for this project will be the Centers for Disease Control and Prevention's 2017 report on Sexually Transmitted Disease Surveillance. It is publically accessible at this link: https://www.cdc.gov/std/stats17/2017-STD-Surveillance-Report_CDC-clearance-9.10.18.pdf   

This data will be used to plot trends in STD growth over the years. Additional data sources may be explored if necessary. 

### Method and Medium

Since the report above is in pdf format, relavent tables from this report will be scraped using Tabula to extract data in a csv format. These tables are available in the report page 68 onwards.  

Once the data has been scraped, the data will be cleaned to plot the following: 
+ Time series graphs of STD growth of the years 
+ Populations most at risk of STDS, by age, sex, and ethnicity
+ States with the highest STDs prevalence rate  

Text accompanying these charts will be gathered from online news articles and the CDC report. The final data story will be created in Shorthand. 

## Part 2: Wireframes and User Research 

### Story Outline 

My visual essay will take the end reader through the story arc described below. 

1. Describing the rising rates of STD prevalence in the United States by visualizing: 
  + A national profile of STDs, charting time series trends in the prevalence of Chlaymidia, Gonorrhea, and Syphillis, from 1941 to 2017. (2 charts, one for cases and one for rate per 100,000 live births) 
  + A breakdown of Chlaymidia, Gonorrhea, and Syphillis, including: Time Series Trends by Cencus Region, and a breakdown for males and females by age group for 2017. (2 charts per disease. Total = 6)
2. Exploring potential reasons for this rise in STD prevalence
3. Using visualizations to identify populations at risk 
4. Documenting existing mechanisms to combat growth in STD prevalence and how alternative policies may be targetted at-risk populations.   

*Note that an original goal of the project was to also provide a breakdown of STDs by race and ethnicity, but due to difficulties in extracting the race/ethnicity data from the source report, those charts have not been included in the story board*  

### User Protocol 

For the purpose of this stage of the project, I began setting up a draft version of the above story line in shorthand. This draft is available at this [link](https://preview.shorthand.com/RLx3VGG1LFUMD1fG).  
I chose to build my wireframes in Datawrapper because of the versatility it offers and because once the data was clean, it was very easy to put the charts together. 
This version is still in its early phases, and was only put together to start soliciting feedback on the first few visualizations before more are built. Therefore, it only includes visualizations for Chlamydia. Similar charts will be built for Gonorrhea and Syphillis based on the feedback collected.

**Target Audience:**  
The target audience for my visual essay will be sexually active individuals in the United States, and health care policy professionals.  
  
**Approach to Identifying Interviewees:**  
Since the target audience is wide enough, I decided to interview my age mates and students in the health care management track at Carnegie Mellon University's Heinz College. 

**Interview Script:**  
To solicit feedback on my wireframes, I prepared the following script: 

"Hi, I'm a second year graduate student taking a "Telling Stories with Data" course this semester. For my final project, I will be developing a visual essay that describes a policy issue through data-driven visualizations. As part of the process, I am preparing early versions of my final visualizations (wireframes) to solicit feedback and see how they can be improved. What I am about to share is only a rough story board presenting a quick depiction of the data to see what can be improved about the charts. The final visualization will be created keeping your feedback in mind. Once you've reviewed the charts, please provide your thoughts on the following questions: 

* *What you think this is?*  

* *Could you describe what this is telling you?*  

* *How long did it take you to arrive at an understanding of this chart?*  

* *Is there anything you find surprising and/or confusing?*  

* *Who do you think is the intended audience for this?*  

* *Is there anything you would change or do differently?*  

* *Do you have any questions for me?*  

Thank you so much for your time!"  

**Feedback:**  
I interviewed three individuals to collect their feedback. Key pieces of insight are included below: 

> "This is telling me STDs in the United States have become more prevalent over time, with Chlamydia being the most widespread of the three that are being analysed." 

> "The data shows that the majority of cases of Chlamydia have been reported by the 20-29 age bracket, for both sexes, and in the South of the United States."  

> "I am surprised at how teens seem to have significantly lesser cases of STDs than 20 plus people, I would have imagined teenagers to be engaging in riskier sexual behaviour than 20 plus adults."  

> "I think the best audience for this would be young people from 20 to 30 who are most sexually active, and are likely to have multiple sexual partners."  

> "A good target audience would be Doctors, health-focused interest groups, researchers."  

> "I’m surprised at how Chlamydia didn’t seem to have a presence in the United States until the mid 1980s."  

> "It may help to have more axis grid lines on the Y-axis for the chart showing Chlamydia cases by census region." 

**Incorporating Feedback**:  
Based on this feedback, I will make sure to clarify that the chart for Chlamydia only begins in the mid 1980s due to unavailability of data for prior years. I will also add more gridlines on the Y-axis for the chart showing Chlamydia cases by census region. I will additionally develop the charts for Gonorrhea, and Syphillis keeping these guidelines in mind. 

## Part 3: The Final Deliverable 

### The Intended Audience 

This piece could have been developed for policy practictioners or sexually active adults in the United States. I decided to narrow my focus to the latter so that individuals at risk of contracting STDs can be appropriately informed and alerted. As a result, I did the following to make sure my visual essay can be as effective as possible: 
* Kept my visualizations simple and easy to digest. Through my user protocol research, I ensured that audience members did not have to spend more than 2-3 minutes pursing all the charts to develop an understanding of the key takeaways
* Used clear and straightforward language to make the text easy to read. I also avoided terms that may be confusing to individuals less well-read on the subject 
* Developed calls to action that were easy to follow and understand so audience members can be persuaded to do their part in controlling the spread of STDs in the United States. 

### Methodology 

My process in developing this essay is summarized below:
1. I began by extracting the relevant tables from the CDC report using Tabula. The extracted tables were cleaned using R and Excel. While I had originally intended to analyse STD prevalence by race as well, I was unable to accomplish this due to difficulties with extracting the Race/Ethnicity tables from the data report. 
2. I set up wireframes in Datawrapper and shared with a few members of the intended audience. Based on their feedback, I decided to truncate the charts depicting the time series trends to only show data from 1980 onwards. Since data on Chlamydia is only available 1980 onwards, this allows for easier comparisions between STDs. I also made sure the scales for the charts comparing STD prevalence between men and women by age were consistent. This ensured that audience members can compare prevalence not only between age groups but between sexes as well. 
3. I researched supporting material to accompany the charts. Much of this material was extracted from the Source Report, but alternative sources were explored where necessary. The full list of references is included at the end of the published visual essay. 
4. The final story was compiled in Shorthand using charts made with both Datawrapper and Infogram. Photographs used in the essay all come from Unsplash, and are credited within the story. 

### Final Data Story

My visual essay is titled "Rising STD Rates in America - An Emerging Healthcare Crisis". It is publicly available at this [link](https://carnegiemellon.shorthandstories.com/RisingSTDRates/index.html). 




 






