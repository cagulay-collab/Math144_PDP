# Math144_PDP
Dataset project for Math-144
### Introduction
For my personal dataset project, I decided to explore trends in breast cancer mortality rates by looking at the education and income of each state. I scraped data from the CDC and combined it with a dataset we used previously, the education and income dataset. 
### Data Processing
In order to carry out the analysis below, I made sure that the number of rows were the same in both datasets by matching up the States column with each other and making sure they were written in the same way. I got rid of two rows from the CDC dataset that accounted for the D.C. area and the United States to make the number of rows even. 
### Exploratory Analysis
The plot below shows a box graph of the breast cancer mortality rates between Democratic and Republican states. Here we see that Republican states tend to have higher breast cancer mortality rates than Democratic states.
<img width="1400" height="865" alt="pdp_visualization2" src="https://github.com/user-attachments/assets/941e3be1-dc86-4f68-84c9-807789b6e7e4" />
I ran a logistic regression model to study the relationship between political parties and breast cancer mortality rates. I used mortality rate as a predictor and political party as the binary outcome. The plot below shows the logistic regression model:
<img width="1168" height="721" alt="image" src="https://github.com/user-attachments/assets/3ebc0326-265d-4126-97a5-96f82c4b28fd" />
I also created scatterplots to understand the relationship between education and income and mortality rates between the two political parties. I ran a linear regression model for these, but they had low coefficients of determinance. 
<img width="1168" height="721" alt="analysis_1" src="https://github.com/user-attachments/assets/6d7174be-fab4-4d18-954a-a4d32524ddd5" />
<img width="1168" height="721" alt="analysis_2" src="https://github.com/user-attachments/assets/744e907f-a223-4e54-a08c-4232b1071073" />
