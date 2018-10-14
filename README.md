# Project_zheng

## Research Proposal
### 1. Goal: question

### 2. What data you can get to answer this question (can your data anwer your questions?)
### If not, what other data you need to construct on your own (from different sources) in order to answer your questions

#### Background
Interests: Financial areas, financial analysis (an assessment of the viability, stability and profitability of a business, sub-business or project.)

Financial analysis may determine if a business will:

1. Continue or discontinue its main operation or part of its business;
2. Make or purchase certain materials in the manufacture of its product;
3. Acquire or rent/lease certain machineries and equipment in the production of its goods;
4. Issue stocks or negotiate for a bank loan to increase its working capital;
5. Make decisions regarding investing or lending capital;
6. Make other decisions that allow management to make an informed selection on various alternatives in the conduct of its business.

One of the most common analysis in finance areas: risk analysis
The process of assessing the likelihood of an adverse event occurring within the corporate, government, or environmental sector. Risk analysis is the study of the underlying uncertainty of a given course of action and refers to the uncertainty of forecasted cash flow streams, variance of portfolio/stock returns, the probability of a project's success or failure, and possible future economic states. 

Read more: Risk Analysis | Investopedia https://www.investopedia.com/terms/r/risk-analysis.asp#ixzz5TsDnNaWb 

In this area, for 

#### Goal: Can we classify/predict if a particular risk in the financial area will happen or not? If avaiable, how much?
For example, 
- giving the performance of some companies, if the companies will close down or not? or how many profits/loss of the companies
- in banking, if we should give these customers loan or not? if these customers will have default in credit card or not?

#### Data:
I found default of credit card clients Data Set in UCI Machine Learning Repository: http://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients

Data Set Information:
There are around 268209 case of customers default payments in Taiwan. 
This research employed a binary variable, default payment (Yes = 1, No = 0), as the response variable. This study rused the following 23 variables as explanatory variables: 
X1: Amount of the given credit (NT dollar): it includes both the individual consumer credit and his/her family (supplementary) credit. 
X2: Gender (1 = male; 2 = female). 
X3: Education (1 = graduate school; 2 = university; 3 = high school; 4 = others). 
X4: Marital status (1 = married; 2 = single; 3 = others). 
X5: Age (year). 
X6 - X11: History of past payment. We tracked the past monthly payment records (from April to September, 2005) as follows: X6 = the repayment status in September, 2005; X7 = the repayment status in August, 2005; . . .;X11 = the repayment status in April, 2005. The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above. 
X12-X17: Amount of bill statement (NT dollar). X12 = amount of bill statement in September, 2005; X13 = amount of bill statement in August, 2005; . . .; X17 = amount of bill statement in April, 2005. 
X18-X23: Amount of previous payment (NT dollar). X18 = amount paid in September, 2005; X19 = amount paid in August, 2005; . . .;X23 = amount paid in April, 2005. 

#### Plan:
In this project, I would like to run different classification models to test and compare how well they classify the binary risk variables. Also, I will try variables reduction methods to see if we can cut some not useful variables, and I will use different regression models to examine how well they predict the probability of the risk. I will also try some methods we learn from this course to see if they can predict well. If there are some methods good for financial data, I am also willing to try.









### Midterm: Visualizations, data, and intinal data explorations process, data cleaning 
