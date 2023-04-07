# ANALYSIS OF THE GENDER GAP IN SPAIN: A MULTIDIMENSIONAL APPROACH

This repository is the result of a final proyect in University of Valencia and provides a sofware built in Python to calculate the Gender-Gap Indicator that we built

The result of this work is the implementation of a Gender Gap Index that provides which provides a global view of the gender gap and also a disaggregated view by economic, social and cultural dimensions.

### Table of Contents
- [Introduction](#intro) 
- [Related work](#rel) 
- [Problem Statement](#prob) 
- [Gender Gap Indicator](#over) 
- [Bibliography](#bib) 
- [Annex](#ann) 


<a name="intro"></a>
## Introduction

Gender equality is a critical issue in the 21st century and a key goal in the United Nations 2030 Agenda for Sustainable Development. Specifically, Sustainable Development Goal (SDG) 5 seeks to achieve gender equality and empower all women and girls. This study contributes to this goal by analysing gender inequality in Spain through a composite indicator that addresses three key dimensions: cultural, social and economic. The indicator developed provides valuable information to identify areas for improvement and measure progress towards gender equality in the country.
Although the initial objective was to make comparisons at the European level, the difficulty in obtaining comparable variables in other countries led to focus only on the national level. However, this limitation does not diminish the importance and relevance of the study, as gender equality is a global challenge that affects all societies, and this specific indicator for Spain can serve as a basis for future research and international comparisons.
This Spain-focused approach allows for a detailed and contextualised assessment of the gender equality situation in the country, which facilitates the identification of specific areas where further intervention and the implementation of effective public policies are required. Furthermore, by analysing gender inequality in economic, social and cultural dimensions, this study provides a comprehensive and holistic perspective of the issue, allowing for a better understanding of the multiple facets of inequality and how they interact with each other.
Ultimately, this study aims to contribute to the achievement of SDG 5 by providing a rigorous and accessible analytical tool to enable policymakers, researchers and other stakeholders to monitor progress towards gender equality in Spain and develop effective interventions to address the inequalities identified.

<a name="rel"></a>
## Related work

There are extensive studies related to the construction of gender indicators. Already in 2006 UNICEF in its annual reports developed a series of indicators that make visible the condition of society and the importance of taking measures in order to achieve real gender equality [2]. Numerous studies also took place in Spain, with the Guide to Gender Indicators of the Junta de Andalucía [3] where, in addition to an extensive definition and framing of these indicators with examples, the importance that these indicators should have both quantitative and qualitative components was stressed. Not only disaggregated indicators have been used in gender studies, undoubtedly the most famous in the field developed by the WEF based on 4 pillars, Economic, Education, Health and Politics, which although being a composite indicator made up of more than 14 variables, does not contain any qualitative component[4]. The latter, in addition to providing an aggregate global vision, also allows us to obtain a disaggregated study and pursues the philosophy of our study, to provide a global and generalised view that at the same time allows us to observe the casuistry of the different areas in order to find points of revision.

<a name="prob"></a>
## Problem statement

We find ourselves in the framework defined by Bourdieu, where he defines social capital, economic capital and cultural capital as the axes that position each individual in society (and even a fourth one, symbolic capital, but which we will not use in this case). As a result of this sociological analysis, we consider these 3 areas as the spaces where discrimination is generated and therefore fields of observation for the phenomenon of the gender gap.

### Aplication 

Once the three dimensions on which we are going to work have been defined, the application of our study will be carried out at the national level. The initial objective was to be able to carry out these analyses also at the European level in order to compare the values obtained, but the difficulty of acquiring the same variables in the other countries has led us to focus on the national level.


By carrying out the calculations at the national level, it allows us to see a temporal evolution in the indicator constructed with the objective of serving as a support for decision-making in public policies that favour citizens with non-discriminatory conditions. Moreover, it is not only a composite indicator to help in decision-making, but also serves as a tool for analysis and comparison year by year of the magnitude of inequality in each period.

The way in which the indicator is established leads us to obtain an aggregate value from the values of the three pillars defined at the beginning (Cultural, Social and Economic). Since the construction of the indicator is a composite value from the results obtained in each pillar, each branch can also be studied individually. In the same way, the value obtained for each pillar can serve as a support for the decisions to be made.

### Data adquisition

The data we needed and acquired were acquired through the official INE website, which provides a large set of gender-segregated data that allows us to explore the best ways to express the three pillar-defined blocks that we focus on with this indicator.

<a name="over"></a>
## GENDER GAP INDICATOR OVERALL

Due to the difficulty of obtaining a large number of different variables, it was decided to choose those that provided a richer time series and could be more representative of the blocks to be staged. Three variables/indicators have been chosen for each of the blocks presented below.

### Economic

The first variable chosen for the study is the wage gap as a clear representative of the gender gap that generates and generates problems that need to be solved by state strategies [6]. The INE provides us with gender-disaggregated data on the average wage with a time series from 2009 to 2020. To obtain the wage gap expressed as a value between 0 and 1 where 1 is the ideal case where your average wage does not depend on your gender and is therefore equal for men and women. The mathematical formulation we have used to express this is defined through the formulas in Figure 1 in the Annex.
Another relevant economic factor of inequality is expressed through the Unemployment Rate, for the context casuistry data were obtained from the INE for men and women separately, with a time series from 2009 to 2021. This unemployment rate is given as a percentage and the calculation of the final indicator is given in Figure 2 of the Annex.
As the last indicator chosen for the creation of the general indicator, the percentage of women in high positions, both public and private, has been chosen as an expression of the possibility of reaching high incomes and positions, it should be expected in a society with absolute equality that reaching a high position does not depend on the gender of the individual. The time series runs from 2011 to 2022 and the formulas to obtain the simple indicator are given in Figure 3 in the Annex.

### Social

The most worrying and most direct case of social discrimination is the Victims of Gender Violence. The series obtained goes from 1999 to 2022 and the formula can be found in Figure 4 of the Annex.

Continuing with the disaggregated social indicators, it has been decided to include the Gender Exclusion Index indicator as it is a reliable international indicator that brings inter-state rigorousness to the global indicator. It also includes certain aspects of society that could not be collected through the data provided by the INE. The value is between 0 and 1, with 1 being the ideal situation where there is no gender exclusion, so no extra calculations are needed. The series runs from 1900 to 2020.
	Finally in the social block it is about Material Deprivation with a time series from 2016 to 2020 which offers another blind view that the study could have. The calculations are expressed in the Annex, Figure 5.
  
  ### Cultural
  
  For the last block, which refers to the cultural environment of Spanish society, the first group studied for the generation of indicators is the percentage of people aged 20-24 who have passed Secondary Education, with data for both men and women separately. These education data have been considered because of their influence on the fundamental development of people's lives and finding a gap in this dimension would be worrying. The data provided in the INE ranges from 2014 to 2021 and the formulas developed can be found in Figure 6 in the Annex.
The last indicator used for the global indicator is the percentage of female researchers as a fundamental source to ensure that scientific progress is not biased by gender, thus producing feedback discrimination in society. The time series for which we have the data starts in 2016 and ends in 2020 and the formulas can be found in Figure 7 of the Annex.

<a name="con"></a>
## Conclusions

The indicator developed in this study serves as a tool for analysis and comparison of gender inequality in Spain in the economic, social and cultural dimensions. This indicator facilitates decision-making in public policies and highlights the areas where greater intervention is required to achieve non-discriminatory conditions and promote a more egalitarian society.

<a name="bib"></a>
## Bibliography

[1] Unidad de Igualdad de Género, Junta de Andalucía.

https://www.juntadeandalucia.es/institutodelamujer/ugen/modulos/Indicadores/bgenero.html
[2] Naciones Unidas PNUD. (2006). Una alianza mundial para el desarrollo. Programa de las Naciones Unidas para el Desarrollo. Informe anual 2006.

[3] Guía de Indicadores de Género (2004). Junta de Andalucía. Mónica Dávila Díaz. https://www.juntadeandalucia.es/institutodelamujer/ugen/sites/default/files/documentos/99.pdf	

[4] Global Gender Gap Report 2022, WEF. https://www3.weforum.org/docs/WEF_GGGR_2022.pdf 

[5] Bourdieu, Pierre (2000). Capital económico, capital cultural y capital social. Desclée de Brouwer. p. 131.164

[6] Serrano Argüeso, M., & Aboitiz Cazalis, M. (2018). ¿Es necesaria en España una ley para combatir la brecha salarial por causa de sexo y de género?. Revista De Trabajo Y Seguridad Social. CEF, (427), 115–149. https://doi.org/10.51302/rtss.2018.1516

<a name="ann"></a>
## Annex

![](/figures/figure1.png)
![](/figures/figure2.png)
![](/figures/figure3.png)
![](/figures/figure4.png)
![](/figures/figure5.png)
![](/figures/figure6.png)
![](/figures/figure7.png)


![Gender Gap Index](/figures/radar_plot.png)

![Temporal Serie](/figures/temporal_plot.png)
