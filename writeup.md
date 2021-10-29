# Classification Model for Bankruptcy Prediction

*Cindy Su*

## Abstract

The goal of this project was to explore wheter classifcation models could be used to identify companies with high Bankruptcy risk.
This information is important for creditors and investors who make loan or investiment to a company. The model help them knowing what companies has high bankrupcy risk and help them make decison

## Design

A company faces bankruptcy when they are unable to pay off their debts. Before a company actually filing bankruptcy, many of the signs will reflect on the financial ratios. This projects aims to build a bankruptcy prediction model based on the data from Taiwan Economic Journal. Taiwan Stock exchange has around 800-900 listed companies, the data used for analysis provides details of company numerical attributes that may help understand the possibility of bankruptcy from 1999 to 2009. Also, I am interested in applying the model on the SP500 company data and analyzing the possibility of whether the company would face high probability of bankruptcy.

## Data

*  [Company Bankruptcy Prediction](https://www.kaggle.com/fedesoriano/company-bankruptcy-prediction/code) 
   - The data were collected from the Taiwan Economic Journal for the years 1999 to 2009. Company bankruptcy was defined based on the business regulations of the Taiwan Stock Exchange.
   - Number of Instances: 6819
   - Number of Attributes: 96
*  [S&P 500 stocks info](https://www.kaggle.com/davidemattioli/sp-500-stocks-info)
   -  The Data is Updated to September 2021 and was taken by yahoo finance.
   -  Number of Attributes: 166

## Algorithms

***Models***

<img width="386" alt="image" src="https://user-images.githubusercontent.com/57165743/139454657-805b7494-d858-4bb2-87df-6f2ce6a85ee8.png">

- KNeighborsClassifier
- DecisionTreeClassifier
- LogisticRegression
- RandomForestClassifier
- BernoulliNB, MultinomialNB, GaussianNB



***Model Evaluation and Selection***

For the creditor or bank, they don't want to suffer from the risk to borrow the money to a company that is going to bankrupt:
low tolerance to high False Negative, and higher tolerance on。False Positive
- The best evaluation metrics were 'roc_auc' and 'Recall'.
- For LogisticRegression model,  needs to use VIF and cormatrix futher identify Multicollinearity and remove multicollinearity features  
### Tools:
- SciKit-Learn: 
- Statsmodels:
- Seaborn
- Matplotlib
- BeautifulSoup
- Selenium
- Pandas
- Numpy

## Communication

The project used powerpoint for the presentation and the python visualisation libraries for the visuals. 
