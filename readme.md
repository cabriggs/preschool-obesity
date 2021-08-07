## Files included

- preschool-obesity-notebook.ipynb: a Jupyter notebook containing the analysis and narrative.
- preschool-obesity-notebook.pdf: a pdf of the Jupter notebook
- preschool-obesity-presentation.mp4: an audiovisual presentation of a summary of the study outcomes 
- preschool-obesity-report.pdf: a report of the study's findings

## Background

For children under five years old, the World Health Organization defines overweight as at least two standard deviations above average BMI, and obesity as at least three standard deviations above. Childhood obesity has been increasing over time, and with it, the associated negative health consequences. It is especially a problem in more developed countries, and in those, among populations with less access to wealth. There are effective public health interventions available when an area likely to benefit from them can be identified.

## Problem statement

The motivating question of this project is: what facts about a county will predict an elevated risk of preschool obesity? Conversely, what conditions will predict a lower prevalence of preschool obesity? By answering this question, we may expect to offer a model which will (1) identify counties which may be primed to experience elevated preschool obesity in the near future, and would thus be well-served by intervention efforts, and (2) identify conditions associated with lowered prevalence of preschool obesity, thereby offering suggestions for potential indirect county-wide preventive interventions.

## What data

I gathered information from City-Data on each of the 3,141 counties in the United States. This collected information includes median income and its recent growth, demographic information (including breakdowns by age, sex, and familial status), poverty rate, percent urban, average commute times, and geographic location.

## What methods

I trained a suite of machine learning models. Different models work better for different data sets, so I compared these models to see which would best predict the house price growth.

### Technology

The analysis was performed in a Jupyter notebook, leveraging the pandas and scikitlearn libraries.

## What conclusions

The best performing model was an ensemble of decision trees. This model explains about 14% of the variation in preschool obesity rates across counties. The predictive power is not nearly as great as for, say, the adult obesity rates, for which the best model can use the same data to explain 68.6% percent of the variation between counties. As a result, an intervention initiative which targets counties at risk of experiencing elevated rates of preschool obesity will not be as effective as those which operate on a smaller level.

## What questions remain

While efficient interventions target adult obesity at the county-level, preschool obesity should be targeted on a more individualized level. A future study should gather household information and attempt to predict preschool obesity rates based on the household data. One potential route is to pair surveyed preschool obesity rates with long-form census data.


