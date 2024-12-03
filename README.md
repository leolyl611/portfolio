# About me

### Research Interests
- Mental Well-being
- Social Engagement

## Education
- __B.A.__ Psychology | University of Toronto May 2026 _(Expected)_

# Research Project
Does Employment status and social engagement predict someone's well-being?

My dataset code: [Mydataset](https://github.com/leolyl611/Mydataset)

## Objectives
- Well-being __highly related__ to an individuals life satisfaction and happiness (Benjamin et al., 2014)
- High rates of anxiety often associated with insecure employment (Wolff, A. D., 2008)
- Those who expect __better__ employment outcomes are happier (Wolff, A. D., 2008)
- Happiness __increases__ with more social exchanges. (Masterson et al. 2021)
- Any forms of social ties can lead to increased well-being (Sandstrom & Dunn., 2014)
- While employment status and social interaction can influence well-being, are they both able to serve as a predictor?
- This research serves to test the question and if one variable can better predict well-being.

## Approach
**Participants**
- N = 7644 adults from an open source dataset in [National Wellbeing Survey](https://www.icpsr.umich.edu/web/ICPSR/studies/38964), a US research study (Monnat et al. 2022)
  - Adults aged 18 to 64 recruited online via Qualtrics sending surveys to emails.
  - *Mean* age = 41; *Standard Deviation*: 13.6
  - 47.8% Male, 51.8% Female, 0.5% Other
- This research will be testing the relationship between employment status and social interaction with life satisfaction using multiple regression.
- This research will be testing another relationship between employment status and social interaction with happiness using multiple regression.
- Age is added as a control variable.

**Measures**
- Life Satisfaction measured through Diemer Satisfaction With Life Scale
  - Cronbach alpha: 0.864
    - Good reliability as alpha value is above 0.8.
    - Items are below 0.9 meaning all items are not too similar to each other.
  - Life Satisfaction Factor Loading range: 0.573 - 0.859
    - Measure has good validity as all values are above 0.4.
    - This measure is a good indicator of life satisfaction.
- Happiness measured via one prompt:
  - *“Taking all things together, would you say you are: Very Happy, Rather Happy, Not Very Happy, Not At All Happy.”*
- Employment Status measured by two items:
  - Yes or no to “One Job”, *“Multiple Jobs”*
- Social Interaction measured via one prompt:
  - *“Thinking about the past 12 months, how often did you engage in the following activities? Get together socially with friends or relatives.”*
  - *"At least once a week, about once or twice a month, A few times, Once or twice, Never"*
 
## Findings
- Although the relationship is weak, we found a __positive__ correlation between employment status, social interaction, and life satisfaction. All three measures increase with each other.
- We also found a weak __positive__ correlation between employment status, social interaction and happiness. All three measures increase with each other.
- There is a strong __postive__ correlation between life satisfaction and happiness. As happiness increases so does life satisfaction indicating that both are good measures of well-being.
- The general trend is that an increase in one measure leads to an increase to all other measures excluding age. This supports prior research with their general trends of employment, social interaction, and well-being.

A multiple regression analysis is conducted testing causation between all measures.

![Pearon Correlation](/assets/img/Corr.png)

Can employment status and social interaction predict Life Satisfaction?
- We found that individuals who are employed and interact more socially leads to __higher__ life satisfaction.
- Age is found to be a significant predictor of life satisfaction.

![SWL Regression](/assets/img/SWL_Regression.png)

Can employment status and social interaction predict Happiness?
- We found that individuals who are employed and have higher amounts of social interaction leads to __higher__ amounts of happiness.

![Happiness Regression](assets/img/Happiness_Regression.png)

# Impact
- Unsurprisingly, happiness and life satisfaction are strong and positively correlated. Both happiness and life satisfactions are strong indicators of well-being consistent with Benjamin et al. (2014) findings.
- Employment and increased social interactions predicts __higher__ life satisfaction and happiness. Both employment status and social interaction are able to predict an individual's well-being.
- However, happiness and life satisfaction are both __better predicted__ by social interaction frequency.
- Although employment status leads to differences in someone's well-being, looking at their social interaction may __better indicate__ their well-being level compared to employment status. This finding can help individuals with low well-being identify the root affecting their well-being.
- **Strengths:** This research uses the national well being survey. It consists a large sample size ensuring strong validity and generalizability across the population.
- **Limitations:** This sample is collected during the pandemic in which evaluations of life satisfaction and happiness may be different compared to post pandemic times.
- **Next step:** A future consideration would be to replicate the study in post pandemic times. It will be interesting to compare the results from different time pressures. By replicating it in post pandemic, we can ensure generalizability across time.

## Publications

1. Benjamin, D. J., Heffetz, O., Kimball, M. S., & Szembrot, N. (2014). Beyond Happiness and Satisfaction: Toward Well-Being Indices Based on Stated Preference. The American Economic Review, 104(9), 2698–2735. https://doi.org/10.1257/aer.104.9.2698
2. De Wolff, A., National Collaborating Centre for Determinants of Health., & National Collaborating Centre for Determinants of Health. (2008). Employment insecurity and health: synthesis paper. NCCDH.
3. Grün, C., Hauser, W., & Rhein, T. (2010). Is Any Job Better than No Job? Life Satisfaction and Re-employment. Journal of Labor Research, 31(3), 285–306. https://doi.org/10.1007/s12122-010-9093-2
4. Masterson, C., Sun, J., Wayne, S. J., & Kluemper, D. (2021). The roller coaster of happiness: An investigation of interns’ happiness variability, LMX, and job-seeking goals. Journal of Vocational Behavior, 131, 103654-. https://doi.org/10.1016/j.jvb.2021.103654
5. [ICPSR Dataset] Monnat, Shannon M., Zhang, Xue, Sun, Yue, Wiemers, Emily E., Wolf, Douglas A., and Montez, Jennifer Karas. National Wellbeing Survey, United States, 2022. Inter-university Consortium for Political and Social Research [distributor], 2024-05-30. https://doi.org/10.3886/ICPSR38964.v2
6. Sandstrom, G. M., & Dunn, E. W. (2014). Social Interactions and Well-Being: The Surprising Power of Weak Ties. Personality & Social Psychology Bulletin, 40(7), 910–922. https://doi.org/10.1177/0146167214529799


