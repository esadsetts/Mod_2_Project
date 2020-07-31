# Mod_2_Project
# Purpose
In this project we investigated which variables are most important in determining a baseball teams wins. I found data from Lahman's baseball database, cleaned the data then engineered new features. I did some exploratory data analysis including plotting the distribution of wins, my target variable.

![wins distribution](https://lh6.googleusercontent.com/qfxD-E0wap7HjNejzKvmqer0QqE0Nf-fK36USJDR2727yMXmPbReQau33sJOcobWmY2t2xHDLa9pT4QOS417Fwsbimra6iNTwI1ZSXVpocZNx7ZwCURz3LG9j225A2IPwSEuUAvQBK4)
I used scikit learn and stats model to create a linear model. I removed highly correlated variables to avoid multi colinearity. I used Lasso and rfe to select the most impactful features. I found that run differential, ops, slg, and fip were very impactful and stolen bases and errors were not very impactful.

![lasso coefficients](https://lh4.googleusercontent.com/NH4I7ZbU50c4s1j6eeizer1q587yk8qbc_hqCF-BFTt7vJoj09acCtZdq1iPaIRgrhTZgE3_4qE_uzkFbCLCPpUf_NmxU9qn7UmnTMI)