# COVID-19 Regression Study

- [Final report](Jackson_Liu_Temlock_Zhang_Lab2_Final_Report.pdf)
- [Source code](src/Jackson_Liu_Temlock_Zhang_Lab2_Final_Report.Rmd)
- [References](src/references.bib)

## Abstract
A study of how COVID-19 case rate is dependent upon US state population demographics (inclusive of Washington D.C.) and mask-related policies using linear regression. The aim was to analyze the relationship between the COVID-19 case rate per 100,000 residents within each state (recorded between January 21, 2020 and October 30, 2020) and the population demographics features, as well as the policy decisions that were or were not put into place in order to combat the rise of COVID-19 cases. Three descriptive linear regression models were developed in an aim to answer the research question.

## Research Question
How is the COVID-19 case rate related to the distribution of population demographics and policy within a state?

## Project Outcomes

After the analysis, it was suggested within the data that the effect of a mask-related policy is something that should not be neglected in comparison to the population demographics. The analysis suggested that the COVID-19 case rate at the state-level is dependent on masks, and that ultimately, there are effective policy and control measures that can be taken by state governments that have some contribution towards combating its spread relative to factors that cannot be controlled such as population demographics. It is noted that these insights are qualified by the assumptions and limitations laid out throughout the report, namely that there are potential issues in meeting the IID assumption and that there is explanatory information that is lost from both the variables investigated as well as the those that were not included in the dataset.

## Tools Used

#### Languages:
- R

#### Libraries:
- tidyverse
- ggplot2
- dplyr
- magrittr
- etc.

## Research Dataset

The research dataset `covid-19.csv` was compiled by Majid Maki-Nayeri, a lecturer at the UC Berkeley School of Information. Many variables were drawn from the COVID-19 US state policy database (Raifman J, Nocka K, Jones D, Bor J, Lipson S, Jay J, and Chan P.). Supporting documents like the specific legal language used by states, additional data sources, and much more are available in unstructured format [here](https://tinyurl.com/statepolicysources).

## Division of Labor

Credit for this project also goes to my team members Aidan Jackson, Frank Liu, and Haoyu Zhang of the UC Berkeley Masters of Information and Data Science program.

All work produced for this project was done in collaboration with my fellow dedicated group members. All members contributed towards the various sections of the report.
