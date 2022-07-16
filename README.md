# My Code to the Alvin-Smart-Money-Management-Classification-Challenge

Hello this is my solution to the alvin smart money prediction challenge. I really enjoyed this challenge mainly due to the fact that it made me think a lot about feature engineering and how to extract more infomation from a limited dataset. This is my solution,hopefully it helps anyone else in feature engineering. At time of publishing this notebook there are still a few days till the competition ends. Good Hunting!

----------------------------------------------------------------------------------------------------------------------------------------------------

# Notebook overview(Please excuse some of the typos in my notebook.)

## 1) Imports and downloads


- download spacy and import most of the machine learning libraries we will need later
- load the data as well



## 2) Basic EDA


- I say "basic EDA" but it is fairly robust in terms of the features I thought of(at least according to me).
- I used the spacy model to get the enitity from the 'MERCHANT_NAME' column. It returns whether the value in 'MERCHANT_NAME' is an ORG(Orginization) or PERSON. using after using .label_ to get more out of the 'MERCHANT_NAME' column as opposed to just label encoding them. 


## 3) Modeling


- I am using lightgbm with the default parameters



## 4) Lastly


- I left some TODOs(what I wanted to improve upon)
- The TODOs that are  markdowns are the most important things that I felt I needed to do.
- The TODOs as comments are the problems I have solved or are minor issues
