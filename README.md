# Project_1_uoft

## Data Cleaning
The "Dec-18" age column was recoded, the like/dislike_hw columns were scaled and recoded as 1-8, and columns not relevant to our analysis were removed.

## Sample Demographics
Descriptive statistics were used to glean demographic information about the sample. The sample size of the dataset used is n = 1175, which is a fairly robust number for a psychology study. Gender distribution was nearly balanced, with males representing 55.2% of the total sample, 44.1% female, and 0.7% preferring not to answer. The age of the sample ranged from under 18 to 60+, with the majority of the sample between the ages of 19-25 (n = 345), followed by 26-32 (n = 241). The occupational distribution showed the majority of the sample being working professionals, (n = 479), followed by students in college (n = 358; an unsurprising finding considering the majority of psychology studies are conducted at universities/colleges).

## Does self-rated sleep cycle quality affect productivity increase?
This research question aimed to explore the impact of sleep quality on productivity increases among participants, utilizing self-rated measures for both sleep cycle quality ("sleep_bal") and productivity increase ("prod_inc"). Each was assessed on a 5-point scale, ranging from -1 (indicating a poor sleep cycle/decrease in productivity) to +1 (indicating an excellent sleep cycle/increase in productivity) in the respective outcomes.

An initial look via box plot revealed the median of productivity increase scores tend to rise in tandem with sleep cycle quality scores. Interestingly, individuals rating their sleep quality as +1 exhibited the broadest distribution productivity outcomes, suggesting high variability within this group. 

To quantitatively assess the relationship between sleep cycle quality and productivity increase, an independent samples t-test was conducted, targeting the mean differences in productivity increase between participants with the lowest and highest sleep quality scores (-1 and +1, respectively). The analysis yielded a p-value of .001, significantly below the alpha threshold of .05, thereby indicating a statistically significant difference in productivity increase between these groups. The t-statistic of -3.1532 further clarifies that participants with higher sleep quality scores report significantly greater improvements in productivity compared to those with lower scores.

This finding underscores the critical role of sleep quality in enhancing productivity. However, given the demographic information of the sample, generalizability of this finding is limited.

## Limitations
The dataset utilized in this study, sourced from Kaggle, presents several limitations that warrant consideration when interpreting these results. Unfortunately very little information was provided about this dataset on Kaggle outside of the variable descriptions and general use of scale measurements. Primarily, the lack of information regarding the temporal and geographic context of the study's execution limits the external validity of our findings. The absence of a specific year and location for the data collection impedes our ability to contextualize the findings within the broader timeline and regional variations of the COVID-19 pandemic. Such contextual factors can influence individual behaviors, stress levels, how long people may have been working from home, and more.

The dataset's reliance on self-reported data inherently carries the risk of self-reporting bias, where participants might underreport or overreport their responses. This issue, compounded by the absence of dtailed methodological information — such as minimally defined scales and survey questions — along with its cross-sectional design and absence of pre-pandemic baselines, significantly hampers our capacity for analysis interpretation and causal inference. Moreover, the demographic skew towards college students and young professionals aged 19-32 further narrows the results' generalizability, making it less representative of broader populations including older adults or individuals beyond academic and professional settings.

In summary, while the dataset provides valuable insights into different work-related psychological outcomes during an unprecedented global health crisis, these findings must be interpreted with consideration of these limitations. 

