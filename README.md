Our png images for our project: folder named "Images"

Our powerpoint: "Project 1 - Group 3.pdf"

Our combined code: "main.ipynb"

Our cleaned data set: "pysco. csv"


![Alt text](image-2.png)

```python
Project : The effects of COVID-19 on work-related psychological outcomes
```
```python
Environments used :
```
csv
pathlib
os
pandas
numpy
matplotlib.pyplot
scipy

# Data Cleaning

The "Dec-18" age column was recoded, the like/dislike_hw columns were scaled and recoded as 1-8, and columns not relevant to our analysis were removed.

# Sample Demographics
```python
Note: The data set was cleaned in a way that made it easier to interpret:
```

Age Range: December 18th was recorded as 12-8
time_bp, time_dp, travel_time are coded in hours
easeof_online, home_env are rated in a 5 point scale (1 = bad, 5 = good)
prodinc, sleepball, newskill, famconnect, relaxed, selftime, are rated in a 5 point scale (-1 to +1)
dropped last column: time_bp.1

Descriptive statistics were used to clean demographic information about the sample. The sample size of the dataset used is n = 1175, which is a fairly robust number for a psychology study. Gender distribution was nearly balanced, with males representing 55.2% of the total sample, 44.1% female, and 0.7% preferring not to answer. The age of the sample ranged from under 18 to 60+, with the majority of the sample between the ages of 19-25 (n = 345), followed by 26-32 (n = 241). The occupational distribution showed the majority of the sample being working professionals, (n = 479), followed by students in college (n = 358; an unsurprising finding considering the majority of psychology studies are conducted at universities/colleges).

# Interpretation of Data

During the pandemic, professionals of all kinds had to start working from home to keep safe. Some workers in certain environments thrive better in an on-site position while others do better working from their own home. We can see that the line of work that had the most difference of opinion are architecture workers. They heavily dislike working from home. This might be because their work requires more in-person site visits and access to certain tools and resources that might not be available at home. The line of work with the least difference in opinion are "Other", but since we can't interpret what that means, next up are teachers. Teachers are nearly equal in their dislike and like of work from home. This might be due to different teaching styles, the content itself of the course, among many other criteria. I think it's interesting to see how many professions agree and disagree of working from home because it provides valuable insights into the varying dynamics of different industries and the diverse needs and preferences of workers. Understanding these perspectives can inform decisions regarding remote work policies, workplace flexibility, and the future of work arrangements.

For the pie chart, I wanted to take a closer look at a specific line of work. I chose engineers because they are the type of worker that seems most likely to like working from home but I was suprised to see that it was nearly equal in their like and dislike. This unexpected finding prompts further investigation into the factors influencing engineers' attitudes toward remote work. It raises questions about the perceived benefits and challenges of working from home within the engineering profession, as well as the impact of individual preferences, job roles, and organizational cultures. Exploring these nuances can provide valuable insights into the complexities of remote work adoption and effectiveness within specific occupational groups.

Note: this was just for curiosity's sake but apparently the acronym APSPDCL means Andhra Pradesh Southern Power Distribution Company Limited which is located in India.

# Q1.Does one's profession influence their level of satisfaction or dissatisfaction with working from home?
There seems to be no steady relationship between the profession and whether the person is satisifed or dissatisfied working from home. Every profession varied in what they do and every answer was either split down the middle or had almost no similarity. Therefore, there is no influence that can be pointed out with this data. However, it's fascinating to observe how individual preferences and circumstances shape one's satisfaction with remote work, regardless of their profession.

# Q2.How do people feel about their home environment?
The pie chart illustrates people's opinion about their home environment during COVD 19 pandemic. According to the chart around 50% of the population indicated that they do not like (strongly dislike and dislike) the home environment. Approximately 25% expressed they like(stronly like and like) their home environment, remainder percentage had a neutral opinion about their home environment. The COVID 19 pandemic necessitated widespread lockdown and social distancing measures, leading many people spend more time at home than usual. Extended time of confinement at home might have led them feel dissatisfaction with the home enviroment and also limited socialisation, remote working and concerns about health and safety could have contributed negative perception of the home environment during pandemic.

# Q3.Is there any relationship between  one’s home environment and dislike working from home?
The first box plot illustrates there is correlation between people's preferences for their home environment and their willingness to work from home. If people strongly dislike their home environment, they might find it challanging to be comfortable working from home, leading to a preference for working in a different environment, like an office or other setting. Conversely if people enjoy their home environment, they may prefer working from home, as it offers them the comfort and convenience they desire.This observation highlights the impotance of considering individuals' preference and comfort levels when implementing remote work policies or making decisions about workplace environments. Understanding and accomadating these preferences can contribute to higher efficiency and overall well being among employees.

# Q4.Is there a change in time spent on work before vs. during the COVID-19 pandemic?
The bar plot visualizes the average work/study hours per day before and during COVID-19 across different occupations. Each bar represents a different occupation, with two bars for each occupation indicating the average hours before and during COVID-19, respectively. The x-axis represents the occupation, while the y-axis represents the average work/study hours. Here's how you can interpret the data:

Comparison: You can compare the height of the two bars for each occupation. A higher bar indicates that people in that occupation spent more hours working or studying during the COVID-19 period compared to before COVID-19.
Impact of COVID-19: Generally, you can observe whether the average work/study hours increased, decreased, or remained relatively stable across different occupations during the COVID-19 period compared to before COVID-19.
Occupational Differences: Look for patterns across occupations. Some occupations may have experienced larger changes in work/study hours than others, indicating varying impacts of the pandemic on different professions.
Color Coding: The bars are color-coded to differentiate between before COVID-19 (medium orchid) and during COVID-19 (medium turquoise) periods, making it easier to visually distinguish between the two.
Legend: The legend at the top right corner explains which color corresponds to each period, making it clear which bar represents which time period.

This data appears to show the average time spent on different activities (time_bp: before COVID-19, time_dp: during COVID-19) for individuals in various occupations.
The data provides insights into how the COVID-19 pandemic has influenced the time allocation of individuals across different occupations. Generally, there is a noticeable shift in time distribution, with some occupations experiencing significant changes compared to others. For instance, individuals currently out of work spent significantly less time on activities during COVID-19, reflecting the challenges in finding new employment opportunities. In contrast, homemakers and retired/senior citizens spent more time on activities during COVID-19, possibly due to increased responsibilities and changes in daily routines caused by lockdowns and restrictions.

Entrepreneurs and medical professionals aiding COVID-19 efforts also saw notable changes, with entrepreneurs spending more time and medical professionals maintaining a high level of engagement. On the other hand, working professionals and students, both in college and school, experienced relatively minor changes in their time allocation. These insights suggest that the pandemic has had a varied impact on individuals' daily lives, with some occupations adapting more significantly to the new circumstances than others.

# Q5.Is there a gender-based preference for remote work or complete physical attendance? 
# If so, what is the ratio of preference between working from home and complete physical attendance among males and females?
These pie charts illustrate the preference for types of work among males and females. Each slice of the pie represents a different preference (e.g., work from home, complete physical attendance). Here's how to interpret the data:

Pie Slices: Each slice of the pie represents a different preference for the type of work. The size of each slice corresponds to the proportion of males or females who selected that preference.
Color Coding: The slices are color-coded to differentiate between different preferences, making it easier to distinguish between them. In this case, 'mediumorchid' and 'mediumturquoise' are used as the colors.
Percentage Labels: Inside each slice, there is a percentage label, indicating the proportion of respondents who chose that preference out of the total number of respondents of that gender.
Title: The title of each pie chart specifies the gender it represents, indicating whether the chart shows preferences for males or females.
By comparing the sizes of the slices within each pie chart, you can see which type of work preference is more common among males and females. If one slice is much larger than the others, it indicates that a large proportion of respondents of that gender prefer that type of work.

Each segment of the pie chart represents a preference category (e.g., working from home, working from the office). The size of each segment corresponds to the proportion of respondents who indicated that preference.
The segment representing the preference for working from home would be larger for female respondents compared to male respondents, indicating a higher proportion of female respondents preferring to work from home.
Conversely, the segment representing the preference for physical attendance at the office would be larger for male respondents compared to female respondents, indicating a higher proportion of male respondents preferring physical attendance at the office.
The difference in segment sizes between male and female respondents illustrates the disparity in preferences for remote work versus physical office attendance between the two genders.
Overall, the interpretation of the pie chart highlights the varying preferences for type of work (remote versus in-office) between male and female respondents, with a larger proportion of female respondents preferring to work from home compared to male respondents.

# Q6. Does self-rated sleep cycle quality affect productivity increase?

This research question aimed to explore the impact of sleep quality on productivity increases among participants, utilizing self-rated measures for both sleep cycle quality ("sleep_bal") and productivity increase ("prod_inc"). Each was assessed on a 5-point scale, ranging from -1 (indicating a poor sleep cycle/decrease in productivity) to +1 (indicating an excellent sleep cycle/increase in productivity) in the respective outcomes.

An initial look via box plot revealed the median of productivity increase scores tend to rise in tandem with sleep cycle quality scores. Interestingly, individuals rating their sleep quality as +1 exhibited the broadest distribution productivity outcomes, suggesting high variability within this group.

To quantitatively assess the relationship between sleep cycle quality and productivity increase, an independent samples t-test was conducted, targeting the mean differences in productivity increase between participants with the lowest and highest sleep quality scores (-1 and +1, respectively). The analysis yielded a p-value of .001, significantly below the alpha threshold of .05, thereby indicating a statistically significant difference in productivity increase between these groups. The t-statistic of -3.1532 further clarifies that participants with higher sleep quality scores report significantly greater improvements in productivity compared to those with lower scores.

This finding underscores the critical role of sleep quality in enhancing productivity. However, given the demographic information of the sample, generalizability of this finding is limited.

# Limitations

The dataset utilized in this study, sourced from Kaggle, presents several limitations that warrant consideration when interpreting these results. Unfortunately very little information was provided about this dataset on Kaggle outside of the variable descriptions and general use of scale measurements. Primarily, the lack of information regarding the temporal and geographic context of the study's execution limits the external validity of our findings. The absence of a specific year and location for the data collection impedes our ability to contextualize the findings within the broader timeline and regional variations of the COVID-19 pandemic. Such contextual factors can influence individual behaviors, stress levels, how long people may have been working from home, and more.

The dataset's reliance on self-reported data inherently carries the risk of self-reporting bias, where participants might underreport or overreport their responses. This issue, compounded by the absence of dtailed methodological information — such as minimally defined scales and survey questions — along with its cross-sectional design and absence of pre-pandemic baselines, significantly hampers our capacity for analysis interpretation and causal inference. Moreover, the demographic skew towards college students and young professionals aged 19-32 further narrows the results' generalizability, making it less representative of broader populations including older adults or individuals beyond academic and professional settings.

In summary, while the dataset provides valuable insights into different work-related psychological outcomes during an unprecedented global health crisis, these findings must be interpreted with consideration of these limitations.

# Conclusion

In conclusion, the analysis of the effects of COVID-19 on work-related psychological outcomes reveals a complex interplay of factors. The pandemic has led to significant changes in work dynamics, with professionals adapting to remote work arrangements. However, the data shows varying preferences for remote work across different professions, highlighting the importance of individual circumstances and job requirements. Additionally, the impact of COVID-19 on daily routines is evident, with shifts in time spent on work and activities. Interestingly, the study also indicates a relationship between self-rated sleep cycle quality and productivity increase, underscoring the importance of sleep in maintaining productivity. Despite these insights, the analysis is limited by the dataset's demographics, potential self-reporting bias, and lack of detailed methodological information. Further research is needed to understand the full extent of COVID-19's impact on work-related psychological outcomes and the role of sleep quality in productivity.
