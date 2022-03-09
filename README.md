# Advanced Regression Assignment
> model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. 
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.
Also, determine the optimal value of lambda for ridge and lasso regression.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
The optimal lambda value in case of Ridge and Lasso is as below:<br>

Ridge - 2 <br>
Lasso - 0.0002 <br>

The Mean Squared error in case of Ridge and Lasso are:<br>
Ridge - 0.0138<br>
Lasso - 0.0139<br>

The Mean Squared Error of Lasso is slightly higher than that of Ridge <br>

Also, since Lasso helps in feature reduction (as the coefficient value of one of the feature became 0), Lasso has a better edge over Ridge.<br>

Hence based on Lasso, the factors that generally affect the increase in price are the Zoning classification, first and second floor swuare feet, Overall quality and condition of the house, Original construction date, Total basement area in square feet and the Basement finished square feet area, Size of the Garage Capacity,

Age of house and Duplex above grade living area square feet negative effect on price.
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python.
- Pandas.
- NumPy
- matplotlib
- sklearn
- Seaborn.
- Jupyter Notebook.
- GitHub.
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Acknowledgements
We Would like to thank:
- S. Anand for explaining the Exploratery Data Analysis Concepts.
- Sajan Kedia for GitHub Sessions.
- Behzad Ahmadi for Python, Pandas and Seaborn Session.
- Anjali Rajvanshi for Linear Regression, Regularization Concepts.
- Upgrad and IIT-B for facilitating the course.


## Contact
Created by [@jagdishj]  - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
