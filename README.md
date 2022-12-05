# DS340W
This project dives into Phishing Detection Models. The main model in this project uses NLP and looks at 4 different types of machine learning methods: 
Decision Trees, Neural Networks, K Nearest Networks, and Support Vector Machines.This model is found in Phishing_email notebook and uses the dataset fraud_email_.csv
which dataset is a collection of more than 2,500 "Nigerian" Fraud Letters, dating from 1998 to 2007 and gathered from Kaggle.com. 

The second model is looking at phishing urls for detection. The data used for this model contains 549,346 entries and this is too large for github but you can access
the data at this link https://www.kaggle.com/datasets/taruntiwarihp/phishing-site-urls. This model is found in the Phishing URL Detection notebook. I had to put it in 
another notebook because I had a fail runtime and not enough ram space when I tried to run an additional five models in one notebook.

The third model looks at detection using phone numbers. This has never been done before so I created my own dataset called phishingPhone.csv. It only has 38 entries. 
You can find this model in the Phishing_email notebook under novelty.
