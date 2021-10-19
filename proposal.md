## Find Your Home Value
<img src="https://user-images.githubusercontent.com/57165743/134412506-78ccf21b-5038-49c9-ad9c-cf7853b08b12.png" width="1000" height="500">

### Motivation:

The home price changes in the bay area are relative in one of the world’s most expensive housing markets. Bay Area home prices in July this year is 24% higher than the same time last summer.
Home prices are influcend by many factors, including the property features, such as size, number of rooms or the garage or its neighborhood...etc. The supply of homes and local economy strength may also affect the prices.

## Summary:

Using any appropriate data source, build classification models that address a useful prediction and/or interpretation 
problem in any domain of interest. Communicate your process and findings in a 5 minute presentation at the end of week 
2 and a short written description.

Metis projects are broken down into 5 component parts -- **design, data, algorithms, tools, and communication** -- that 
are each scored individually. Below is a description of each component as it relates to this project. For more detail 
on how these components are graded and how extra points are rewarded, refer to the [project success guide](./project_success_guide.md).  


### Design:

*  The project should be centered around a **well-posed classification problem** in a domain of interest that can be reasonably addressed by available data


### Data:
   
*  The data can be acquired by any means: straightforward downloads, use of APIs, web scraping, etc.
*  Make sure that you have a **discrete target variable** to predict. Aim to have **10,000+ data points** and 
**10+ features** so that you can build a robust model with interesting feature engineering and selection challenges; 
consult with an instructor if you are considering deviating from this rule of thumb, which is often fine.

 
### Algorithms

*  Building a **classification model** in python is required, including trying at least several of the classification models 
covered during the course and using class imbalance techniques and feature engineering as appropriate. You should also 
spend extra time thinking about **feature engineering**. How can you come up with representations of the data that are really 
relevant to the business / the predictive problem, and demonstrate that the features you've engineered add predictive value?
*  **Rigorous model selection and evaluation** (i.e. proper validation and testing) is required, using appropriate classification metrics
*  Other classification methods and metrics (beyond those covered in the course) are optional

### Tools

*  Use the **python packages for classification models** (sklearn, xgboost, etc.) that were covered in class
*  Other tools not covered in the course are optional but welcome. We highly encourage you to use at least one and 
preferably more of these optional tools to address at least one of storage/infrastructure, processing, visualization, 
and production.
*  Major examples of applicable tools not covered in the course:
   - Storage tools could include SQL or noSQL (e.g. MongoDB) databases
   - Processing tools could include Google Cloud or Amazon Web Services for cloud computing resources
   - Visualization tools could include python libraries such as Bokeh and Plotly or resources outside of python such as Tableau
   - Production tools could include Flask or other web app libraries/technologies
   - 



### Goals:
 This project would like to using these related features to predict the house price in Bay Area. 
- (1) Showing the average price in Bay area 
- (2) Suggest what is value of the house ?  -  Is the price listed by the realter overpriced within a reasonable range
- (3) House price predictions for next 5 years

<img src="https://user-images.githubusercontent.com/57165743/134410589-c7100111-9a9b-41b0-abfa-12b972a0695c.png" width="400" height="400">
  ** The analysis will be focusing on East Bay and South first, and will include Peninsula and SF area if time is allowed.

### Data:
- [Zillow](https://www.zillow.com/)
- [Realtor](https://www.realtor.com/)
- [Median Household Income in California](http://zipatlas.com/us/ca/zip-code-comparison/median-household-income.htm)

### Tools:
- SciKit-Learn: 
- Statsmodels:
- Seaborn
- Matplotlib
- BeautifulSoup
- Selenium
- Pandas
- Numpy

### Credit:
- [Bay Area Market Reports](https://www.bayareamarketreports.com/trend/san-francisco-home-prices-market-trends-news)
- [Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)
- [Ref info](https://github.com/ogunlao/HousePricePrediction/blob/master/decock.pdf)


### Bkup Topic:
- Topic: Predict the movie sales revenue 
- Data: boxofficemojo.com, imdb.com
