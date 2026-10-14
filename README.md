# Bank Marketing Subscription Analysis

Exploratory data analysis of the [UCI Bank Marketing dataset](https://archive.ics.uci.edu/dataset/222/bank+marketing), which records a Portuguese bank's phone marketing campaigns. The goal of the team project was to predict whether a client would subscribe to a term deposit.

**My role:** I led the exploratory data analysis (EDA) for our STAT 4365 group project.

## What I did
- Compared subscribers and non-subscribers across client and campaign variables using group summaries
- Built cross-tabulations of subscription rate by job, education level, and marital status
- Plotted distributions of age, account balance, and number of campaign contacts by subscription status

## Key findings
- Subscribers had more than twice as many contacts from previous campaigns as non-subscribers (1.09 vs. 0.47 on average)
- Subscribers were less likely to have a housing loan (42% vs. 58%)
- Subscribers needed fewer contacts during the current campaign (2.3 vs. 2.9 on average)

## Tools
Python, pandas, matplotlib, seaborn, Jupyter Notebook

## Data
4,521 client records with 16 features. Call duration was removed because it is only known after a call ends, which would leak the outcome into the model.
