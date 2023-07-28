# Number of Fires by Cause Class in Canada (1990-2021)
By: Brendan Yuen, Daniel Ma, Jiayi Zou, Elmeri Hakkinen


# **Introduction**
Backgroud:\
Forest fires are a significant environmental concern in Canada due to the country's vast forested areas and diverse climatic conditions. These fires can have severe ecological, economic, and social impacts on the affected regions. Understanding the causes and patterns of forest fires is essential for developing effective strategies for prevention, mitigation, and response.

Question will try to answer: ???

About the dataset:\
This dataset contains information on the causes and frequency of forest fires that occurred in various jurisdictions (administrative regions) across Canada from 1990 to 2021, in English and French. The varibles are:
* Year / Année: This column represents the year when the forest fire incidents occurred.
* ISO: This column contains the ISO code corresponding to the specific geographic region or province where each fire incident took place.
* Jurisdiction / Juridiction: This column indicates the administrative region or jurisdiction responsible for the area where the fire incident occurred.
* Cause / Origine: This column categorizes the primary reason behind each fire incident. The causes include Human activity, Lightning, Prescribed burn, Reburn and Unspecified.
* Number / Nombre: This column represents the numerical count of fire incidents recorded for each specific combination of year, ISO code, and cause.
* Data Qualifier / Qualificatifs de données: Data Qualifier: An indicator of data quality or reliability, specifying if the data is provisional, confirmed, or estimated.

The data could be used for various analyses, such as identifying trends in fire incidents, understanding the impact of different causes, and formulating effective fire management and prevention strategies.



# **Preliminary Results**

# **Methods: Plan**

While the plots and estimates derived from the data provide valuable insights into the wildfire characteristics and trends, they may not be sufficient analysis for informed decision-making. Plots and estimates alone do not provide statistical evidence to support any significant differences or trends observed in the data. Stakeholders require more robust evidence, such as hypothesis tests and confidence intervals, to understand the reliability and generalizability of the findings.

To address the gap and provide more reliable conclusions, additional analyses are essential. Two statistical tools, namely hypothesis testing and confidence intervals, will be employed to enhance the significance and credibility of the results.

1.	**Hypothesis Testing**: We will perform a hypothesis test to investigate whether there is a significant difference in the mean and standard deviation fire size between specific years. The null hypothesis will state that there is no significant difference, while the alternative hypothesis will suggest a significant difference in fire size.

The following null and alternative hypotheses were formulated for hypothesis testing:

* Null Hypothesis (H0): There is no significant difference in the mean fire size between the selected years. µ1 - µ2 = 0, where µ1 are the mean values from 1990 – 2005 and µ2 are mean values from 2006 – 2021. 
There is no significant difference in the standard deviation of fire size between the selected years. σ1 – σ2 = 0, where µ σ1 are the standard deviation values from 1990 – 2005 and σ2 are standard deviation values from 2006 – 2021.

* Alternative Hypothesis (Ha): There is a significant difference in the mean fire size between the selected years. µ1 - µ2 ≠ 0, where µ1 are the mean values from 1990 – 2005 and µ2 are mean values from 2006 – 2021.
There is a significant difference in the standard deviation of fire size between the selected years. σ1 – σ2 ≠ 0, where µ σ1 are the standard deviation values from 1990 – 2005 and σ2 are standard deviation values from 2006 – 2021.


2.	**Confidence Intervals**: Confidence intervals will be calculated for relevant parameters, such as the difference in means between two years. These intervals will provide a range of plausible values for the population parameter and offer insights into the precision and reliability of the estimates.


**Expectations and Potential Impact of Findings**

We expect that the hypothesis test and confidence intervals will provide statistically significant evidence of differences in fire size between certain years. The results will likely reveal variations in fire occurrence and severity over time, shedding light on potential trends and patterns.
Such findings can have significant implications for policymakers, forest managers, and other stakeholders. Understanding the temporal changes in wildfire characteristics can aid in the development of targeted strategies for wildfire prevention, mitigation, and response. The results could inform resource allocation, fire risk assessment, and the implementation of effective measures to protect communities and ecosystems.

**Future Questions**

The results of this study may raise further research questions and avenues for exploration. For instance, understanding the factors contributing to the observed changes in fire size could lead to investigations into climate patterns, land-use changes, or fire management practices. Additionally, the impact of wildfires on biodiversity, air quality, and human health could be areas for future research, aiming to develop more comprehensive wildfire management strategies.

# **Resources**
* Forest Fires | National Forestry Database. (n.d.). Retrieved from nfdp.ccfm.org website: http://nfdp.ccfm.org/en/data/fires.php 

**References**
* Coogan, S. C. P., Daniels, L. D., Boychuk, D., Burton, P. J., Flannigan, M. D., Gauthier, S., … Wotton, B. M. (2021). Fifty years of wildland fire science in Canada. Canadian Journal of Forest Research, 51(2), 283–302. https://doi.org/10.1139/cjfr-2020-0314 
* Owens, B. (2023). Why are the Canadian wildfires so bad this year? Nature, 618. https://doi.org/10.1038/d41586-023-01902-4
