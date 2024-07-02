# Insight-into-Aspirations
Executive Summary: This research explores the relationship between women's educational aspirations and desired family size, delving into the multifaceted dynamics that shape fertility choices. Using a Poisson Regression model and Negative Binomial model, I examined the impact of educational aspirations, education, religiosity, employment, and other factors on women's preferences regarding the number of children they wish to have. Findings reveal a significant and negative correlation, between aspirations and the number of children women desire to have, highlighting the influence of educational pursuits on fertility trajectories. Government initiatives can support women prioritizing education and family planning by encouraging universities to offer flexible study options and providing financial incentives such as scholarships and grants. Additionally, instituting workplace policies like flexible hours and remote work can help women balance their educational, professional, and familial responsibilities.

![Ed_Asp](https://github.com/DalJoshThomas/Insight-into-Aspirations/blob/main/Ed_Asp.png)


Data: I collected data using a Google form, which can be seen with this link (https://forms.gle/zpyB4VtDkH2W7iMd7). All variables were not used in the final model because some were not significant, regardless of the specifications attempted.

Methodology: The Poisson Maximum Likelihood estimation method was chosen, due to its ability to capture count data effectively. Under this method, the mean should be relatively close to the variance, which is generally the case with fertility data. The Poisson distribution is appropriate for non-negative integer data and is particularly useful when data has a right-skewed distribution, which is often the case with fertility data. The Negative Binomial model was used since the count data exhibits underdispersion. The NB model account is useful where the assumption of the Poisson model is violated, that assumption being the expected value being equal to the variance.

Skills : 

R : dplyr,ggplot2,stats,MASS,glm,readxl,carr,corrplott
Power BI : data transformation, data modeling, visualization and reporting, customization and integration, data insights

Recommendations:
In formulating policy recommendations, it is imperative to ensure that the proposed policies not only foster high educational attainment but also contribute to favorable fertility rates, recognizing both as pivotal elements for sustained economic growth and development. The underpinning theories of the quantity-quality model and life course perspective accurately describe the findings, necessitating policies that mitigate the opportunity cost of childbearing while concurrently enabling the provision of a higher standard of living for their children.
       
Firstly, governmental initiatives can encourage universities to adopt flexible educational policies tailored to the needs of women who prioritize education and having children. This encompasses the introduction of part-time study options, online course offerings, and extended timelines for completing educational programs. Such measures aim to empower women to pursue their educational objectives without succumbing to pressure to defer family planning.

Secondly, government intervention can manifest in the provision of financial support, scholarships, or incentivization programs specifically designed for women undertaking higher education. This strategic approach seeks to alleviate the financial constraints associated with educational pursuits, rendering it more feasible for women to integrate their academic pursuits with considerations of family planning.

Finally, the government can play a pivotal role in instituting supportive workplace policies that cater to the transitional phase from education to the workforce. Policies encompassing flexible work hours, remote work options, and family leave not only accommodate women's commitment to education and career development but also facilitates the integration of their professional and familial responsibilities. 

Next Steps:
Future research should aim to address these limitations by employing diverse research methods, incorporating longitudinal data, and exploring additional variables that might contribute to a more comprehensive understanding of fertility preferences. Longitudinal data would be essential for examining how preferences for family size evolve.	

This repository includes the R markdown file, HTML file, Power BI report and the research paper.
