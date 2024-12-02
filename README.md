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
- While employment status and social interaction can each lead to varying levels of well-being, are they both able to serve as a predictor?
- This research serves to test the question and if one variable can better predict well-being.

## Approach
Participants
- N = 7644 adults from an open source dataset in [National Wellbeing Survey](https://www.icpsr.umich.edu/web/ICPSR/studies/38964), a US research study (Monnat et al. 2022)
  - Adults aged 18 to 64 recruited online via Qualtrics sending surveys to emails.
  - *Mean* age = 41; *Standard Deviation*: 13.6
  - 47.8% Male, 51.8% Female, 0.5% Other
- This research will be testing the relationship between employment status and social interaction with life satisfaction using multiple regression.
- This research will be testing another relationshiip between employment status and socail interaction with happiness using multiple regression.
- Age is added as a control variable.

Measures
- Life Satisfaction measured through Diemer Satisfaction With Life Scale
  - Cronbach alpha: 0.864
    - Good reliability as alpha value is above 0.8.
    - Items are below 0.9 meaning not all items are similar too each other.
  - Life Satisfaction Factor Loading range: 0.573 - 0.859
    - Good validity as all values are above 0.4.
- Happiness measured via one prompt:
  - *“Taking all things together, would you say you are: Very Happy, Rather Happy, Not Very Happy, Not At All Happy.”*
- Employment Status measured by two items:
  - Yes or no to “One Job”, *“Multiple Jobs”*
- Social Interaction measured via one prompt:
  - *“Thinking about the past 12 months, how often did you engage in the following activities? Get together socially with friends or relatives.”*
  - *"At least once a week, about once or twice a month, A few times, Once or twice, Never"*
 
## Findings
- We found a significant __weak positive__ correlation between Employment status, Social Interaction and Life Satisfaction.
- We also found a significant __weak positive__ correlation between Employment status, Social Interaction and Happiness.
- There is a significant __strong postive__ correlation between Life Satisfaction and Happiness indicating that both measures are good indicators of well-being
- The general trend is that one variable leads to an increase to all other variables excluding age. This supports prior research with their general trends of employment, social interaction, and well-being

A multiple regression analysis is conducted for this test testing causation from pearson correlations.

![Pearon Correlation](/assets/img/Corr.png)

Can employment status and social interaction predict Life Satisfaction?
- We found that that individuals who are employed and socially interact more leads to __higher__ life satisfaction.
- Age is found to be significant predictor of life satisfaction.

![SWL Regression](/assets/img/SWL_Regression.png)

Can employment status and social interaction predict Happiness?
- We found that individuals who are employed and have __higher__ amounts of social interaction leads to higher amounts of happiness.

![Happiness Regression](assets/img/Happiness_Regression.png)

# Impact
- Unsurprisingly, happiness and life satisfaction contain strong positive correlations. Both happiness and life satisfactions are strong indicators of well-being consistent with (Benjamin et al., 2014) findings.
- Employment and increased social interactions predicts __higher__ SWL and happiness. Both employment status and social interaction are able to predict an individual's well-being.
- However, happiness and life satisfaction are both __better predicted__ by Social interaction frequency.
- Although employment status leads to differences in someone's well-being, looking at their social interaction may __better indicate__ their well-being level compared to employment status. This finding can help individuals with low well-being
- Strengths: This research uses the national well being survey. It consists a large sample size ensuring strong validity and generalizability across the population.
- Limitations: This sample collected during during the pandemic in which evaluations of satisfaction with life and happiness may be different compared to post pandemic times.
- Next step: A future consideration would be to replicate the study in post pandemic times. It will be interesting to compare the results from different time pressures. However by replicating it in post pandemic, we can ensure generalizability across time.

## Publications

1. Benjamin, D. J., Heffetz, O., Kimball, M. S., & Szembrot, N. (2014). Beyond Happiness and Satisfaction: Toward Well-Being Indices Based on Stated Preference. The American Economic Review, 104(9), 2698–2735. https://doi.org/10.1257/aer.104.9.2698
2. De Wolff, A., National Collaborating Centre for Determinants of Health., & National Collaborating Centre for Determinants of Health. (2008). Employment insecurity and health: synthesis paper. NCCDH.
3. Grün, C., Hauser, W., & Rhein, T. (2010). Is Any Job Better than No Job? Life Satisfaction and Re-employment. Journal of Labor Research, 31(3), 285–306. https://doi.org/10.1007/s12122-010-9093-2
4. Masterson, C., Sun, J., Wayne, S. J., & Kluemper, D. (2021). The roller coaster of happiness: An investigation of interns’ happiness variability, LMX, and job-seeking goals. Journal of Vocational Behavior, 131, 103654-. https://doi.org/10.1016/j.jvb.2021.103654
5. Monnat, Shannon M., Zhang, Xue, Sun, Yue, Wiemers, Emily E., Wolf, Douglas A., and Montez, Jennifer Karas. National Wellbeing Survey, United States, 2022. Inter-university Consortium for Political and Social Research [distributor], 2024-05-30. https://doi.org/10.3886/ICPSR38964.v2
6. Sandstrom, G. M., & Dunn, E. W. (2014). Social Interactions and Well-Being: The Surprising Power of Weak Ties. Personality & Social Psychology Bulletin, 40(7), 910–922. https://doi.org/10.1177/0146167214529799

