# Math144_PDP
Dataset project for Math-144
### Introduction
For my personal dataset project, I decided to explore trends in breast cancer mortality rates by looking at the education and income of each state. I combined two datasets: one from the CDC that provides information on the breast cancer mortality rate in all females in every state; and a dataset we used previously, the education and income dataset. 
### Data Processing
In order to carry out the analysis below, I made sure that the number of rows were the same in both datasets by matching up the States column with each other and making sure they were written in the same way. I got rid of two rows from the CDC dataset that accounted for the D.C. area and the United States to make the number of rows even. I then combined the two datasets.
### Exploratory Analysis
The plot below shows a box plot of the breast cancer mortality rates between Democratic and Republican states. Here we see that Republican states tend to have higher breast cancer mortality rates than Democratic states.
<img width="1400" height="865" alt="pdp_visualization2" src="https://github.com/cagulay-collab/Math144_PDP/blob/25abf3611f5ce972600e846cdae58faa11845535/updates_boxplot.png" />
### Logistic Regression
I ran a logistic regression model to see if mortality rates can predict political party. The model correctly classified 64% of the political parties. The figure below shows the predicted probability of political party:
<img width="1168" height="721" alt="image" src="https://github.com/user-attachments/assets/3ebc0326-265d-4126-97a5-96f82c4b28fd" />
### Linear Regression
I also created scatterplots to understand the relationship between education and income and mortality rates between the two political parties. I ran a linear regression model for these, but they had low coefficients of determinance. The linear model that predicted mortality rate based on per capita income and political party explained 27.57% of the variance. 
<img width="1168" height="721" alt="analysis_1" src="https://github.com/cagulay-collab/Math144_PDP/blob/a70f626d990e32066c8faa27df0174249e9f5df7/updated_per.capita.income%20graph.png"/>
The linear model that predicted mortality rate based on percentage of advanced degree holders and political party explained 13.88% of the variance.
<img width="1168" height="721" alt="analysis_2" src="https://github.com/cagulay-collab/Math144_PDP/blob/a70f626d990e32066c8faa27df0174249e9f5df7/updated_adv.perc%20graph.png" />
