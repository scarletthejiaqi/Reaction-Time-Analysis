# Reaction Time Prediction Project

## Abstract

In this study, we aimed to determine how various conditions affect reaction times and to develop a predictive model that accurately forecasts these times.  
Our exploratory data analysis suggested minimal effects from variables such as sleep duration, caffeine intake, class, and fatigue levels, leading to further model refinement.  
By employing backward and bidirectional elimination methods, we identified device usage, visual acuity, age, and WiFi connectivity as significant predictors.  
We used model diagnostics and Box-Cox transformation, leading to better prediction results.

## Discussion of Results and Conclusions

Our initial hypothesis posited that sleep duration and caffeine intake were primary predictors of reaction time. However, our findings contradicted this hypothesis, showing that these factors were not as influential as anticipated.

### Key Findings:
- **Device Usage**: The choice of participation devices significantly affects reaction time, particularly for those using Windows desktops to complete the test. This result may be attributed to the preference for desktops for gaming, which requires fast reaction times.
- **Visual Acuity**: Higher visual acuity allows for more rapid and precise detection of visual stimuli, leading to faster reaction times.
- **Age**: As people age, they generally require more time to react compared to younger individuals.
- **WiFi Connectivity**: Poor WiFi connections result in greater time lags, leading to higher reaction times during the test.

## Challenges

This project faced several challenges, including:  
- **Small Sample Sizes**: Certain groups, such as specific device types and alcohol levels, had small sample sizes, limiting the generalizability of our findings.  
- **Complex Variable Interactions**: Isolating the impact of individual variables on reaction times was complex due to the intertwined nature of factors like sleep, caffeine intake, and device usage.

## Future Prospect

We hypothesize that individual differences in reaction time are more significant than other factors. Therefore, we propose using paired data from the same individuals under different conditions.  
This approach may yield more accurate comparisons and results.

## Repository Contents

- `Survey.csv`: Contains the datasets used for analysis.
- `Reaction Time Analysis Report.pdf`: Report of the findings.
- `Reaction Time.Rmd`: Includes scripts for data preprocessing, analysis, modeling and model diagnostics.
- `README.md`: Project overview and key findings.

