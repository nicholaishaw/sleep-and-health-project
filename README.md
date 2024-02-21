# The Effect of Stress Level and Physical Activity on Sleep Duration 

## Background
Research samples of the American population have revealed that as many as 50% of Americans have difficulty initiating and maintaining sleep (Crowley, 2011). In addition, other analyses report that just under 20% of Americans experience daytime drowsiness (Slater & Steier, 2012). Recent health findings report that sleeping less than 7 hours a night is associated with an increased risk for various health complications such as diabetes, heart disease, and overall mortality (Liu et al., 2016). Research has also reported the association of lack of sleep and mental dysfunction as well. For instance, Liu (2016) discusses that poor sleep habits are associated with cognitive dysfunction. Since prior research shows that many Americans have sleep-related difficulty and will experience the subsequent effects of sleep loss, our analysis informs us of ways some individuals can obtain more sleep.

## Data Exploration
**Physical activity and sleep.** We selected a dataset from Kaggle to explore the relationship between physical health and sleep (Möbius, 2020). of Fitbits were given to 30 participants and their physical activity levels and sleep durations across 31 days. Fitbit categorized the number of hours each participant spent in certain metabolic zones as either sedentary (heart rate below 50% of maximum heart rate), lightly active (heart rate between 50% and 69% of maximum heart rate), fairly active (heart rate between 70% and 84% of maximum heart rate), and very active (heart rate greater than 85% of maximum heart rate). Fitbits stored each participants' sleep duration as total minutes asleep. in We hypothesized that physical activity levels (sedentary, lightly active, fairly active, and very active) would be positively associated with total sleep duration.

**Stress level and sleep.** Using a dataset from Kaggle, we examined the link between mental health and sleep (Tharmalingam, 2023). In this dataset, 374 participants were recruited and surveyed about their sleep duration (average number of hours slept per night) and self-reported stress level (a likert scale of 1-10, 1 indicating very low stress and 10 indicating extreme levels of stress). The participants' resting heart rate was also collected. We hypothesized that there is a negative correlation between self-reported stress level and sleep duration as well and a negative correlation between resting heart rate and hours asleep.

## Data Cleaning


## Results
**Physical activity level and sleep.** We conducted an analysis of thirty participants using Jupyter Notebook from a public dataset on Kaggle (Möbius, 2020). We found there was no significant correlation between very active exercise and hours asleep (*p*=0.066, *r*=-0.090). We found a significant negative association between hours of sedentary activity and hours asleep (*p*=1.220e-41, *r*=-0.599). We found a significant negative association between hours of fairly active exercise and hours asleep (*p*=4.877e-07, *r*=-0.245). We found no significant association between lightly active exercise and hours asleep (*p*=0.505, *r*=-0.033). 

**Self-reported stress level and sleep.** We conducted an analysis of 374 participants using Jupyter Notebook obtained from a public dataset in Kaggle (Tharmalingam, 2023). We found that there was a significant negative association between self-reported level of stress and hours asleep (*p*=1.238e-88, *r*=-0.811). We found a significant positive association between heart rate and stress level (*p*=4.492e-50, *r*=0.670). We found a significant negative association between stress level and hours asleep (*p*=6.915e-27, *r*=-0.516). As such, we reject the null hypothesis that stress level does not impact sleep duration.


## References
Crowley, K. (2011). Sleep and sleep disorders in older adults. _Neuropsychology review_, _21_, 41-53.

Liu, Y., Wheaton, A. G., Chapman, D. P., Cunningham, T. J., Lu, H., & Croft, J. B. (2016). Prevalence of healthy sleep duration among adults—United States, 2014. __Morbidity and Mortality Weekly Report_, 65_(6), 137-141.

Möbius. (2020, December 16). _Fitbit Fitness Tracker Data_. Kaggle. https://www.kaggle.com/datasets/arashnic/fitbit 

Slater, G., & Steier, J. (2012). Excessive daytime sleepiness in sleep disorders. _Journal of thoracic disease, 4_(6), 608.

Tharmalingam, L. (2023, May 26). _Sleep health and lifestyle dataset. Kaggle_. https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset
