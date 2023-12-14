# THE INDIAN STARTUP ECOSYSTEM DATA ANALYSIS FOR ENTREPRENEURS

This project aims to provide valuable insights into the factors that significantly impact the funding received by startups in India. By analyzing data from 2018 to 2021, we explore how various factors, including Sector, Headquarters(location), Company focus, and Funding stage, influence the amount of funding startups receive. The purpose of this analysis is to guide a potential team of entrepreneurs in making informed decisions when venturing into the Indian startup ecosystem.

## Libraries to install 
### For numerical computation and data analysis
 * import numpy as np
 * import pandas as pd
### For data visualization
 * import matplotlib.pyplot as plt
 * import seaborn as sns
### Other supporting libraries 
 * import pyodbc
 * from dotenv import dotenv_values
 * import statsmodels.api as sm
 * from statsmodels.formula.api import ols
 * import warnings

## Columns 
 * Company/Brand
 * Stage
 * Amount($)
 * HeadQuarter
 * What it does
 * Sector
 * Funded Year
 * Founded
 * Investor

## Hypothesis
 * Ho (Null hypo) : There is no significant association between the funding amount and the other factors such as sector,location, and the funding stage.

 * H1 (Alternate hypo) : There is a significant association between funding amount and other factors such as sector, location, and funding stage.

## Limitations
1. The accuracy and completeness of the data used for analysis can impact the reliability of the results. Incomplete or inaccurate data may lead to biased conclusions and limit the scope of the analysis.
2. The source of the data might have its limitations, and the accuracy of the information may vary, affecting the validity of the analysis.
3. The dataset used for analysis does not represent the entire population of Indian startups, potentially introducing selection bias
4. Sector categorization might be subjective and prone to misclassification. Different sources or methodologies for sector classification could yield different results.
5. Some relevant variables, such as company growth metrics,and market competitiveness, might not be included in the dataset. These factors can significantly influence funding decisions but were not accounted for in the analysis as they were not available in the dataset.
   
## Outcome 
Based on the ANOVA results,we reject the null hypothesis (H0) for the "Stage" variable and conclude that there is a significant association between the funding amount and the "Stage" variable. This means that a Startup B in the more advanced "Series D" stage will  receive a significantly higher amount of funding compared to Startup A in the early "Seed" stage. 
However, for the "Sector" and "HeadQuarter" variables, we fail to reject the null hypothesis, indicating that there is no significant association between the funding amount and these variables. Eventhough some sectors and companies in specific location attracted more funding per the analysis, generally, companies in different sectors and locations get similar level of funds.   
## Recommendations
1. Consider sectors like Fintech, Edtech and Retail when venturing into this ecosystems, however be mmindful of the competition in such sectors.
2. Conduct thorough market research to identify potential investors interested in your sector and offerings as the main investors are unkown to the public.
3. Tailor fundraising efforts based on the investment stage. Debt seems to be the main source of funding for startups in the Indian business ecosystem. due diligence must be done to find out what stage suits growth phase.  
4. Companies in cities such as Gurgaon, Bangalore, Hyderabad,Mumbai, NewDelhi and Jodhbur received quite significant funding within the period. In this cities except for Gurgaon, getting funded irrespective of Sector is highly attainable.

## Conclusion
The analysis of funding patterns in the Indian startup ecosystem provides valuable insights for entrepreneurs and investors alike. The data indicates a positive trend of increasing funding over the years, with specific investors who are Unknown  and Silver Lake playing significant roles in supporting startups. However, there are still challenges represented by the "None" and "Nan" categories, which may require further investigation and data improvement efforts.

## References
https://www.ibm.com/docs/en/spss-modeler/saas?topic=dm-crisp-help-overview

2022 EPRA International Journal of Multidisciplinary Research (IJMR) - Peer Reviewed Journal | www.eprajournals.com | Journal DOI URL: https://doi.org/10.36713/epra2013

https://www.neusourcestartup.com/startupindia/startup-problems-india-facing

https://www.theofficepass.com/toppings/common-problems-entrepreneurs-face-starting-startup-india.html

## Authors
Enoch Taylor-Nketiah         | Doe Edinam Abla            | Kofi Asare Bamfo           | Timothy Morenikeji Akinremi         | Tolulope Philip Oludipe   | Godfrey Chilebe

https://github.com/kojoboyoo | https://github.com/doeabla | https://github.com/akbamfo | https://github.com/timothyakinremi

follow me on linkedin - https://www.linkedin.com/pulse/indian-startup-ecosystem-enoch-taylor-nketiah%3FtrackingId=jCEVr7E12p377%252BgWF0WLxA%253D%253D/?trackingId=jCEVr7E12p377%2BgWF0WLxA%3D%3D
