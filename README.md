# Lending Club Case Study
> A Case study to filter the applicants on the basis of not paying the laon or defaulting the loan.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- The company is trying to reach a decision whether to give a loan to a certain individual or not, thus reducing two types of risks: 
    - If the person is likely to repay the loan, then not approving the loan will result in loss of business 
    - If the person is not likely to repay the loan, then approving the loan will result in financial loss 

## Observations
- Scenarios where customers defaulted:
    - Customers with 'Mortgages home' and higher annual income in year 2008 - defaulted the most.
    - Customers with 'Mortgages home' and higher annual income in year 2011 - defaulted the most.
    - Customers with 'Other home' with higher Loan Amount in year 2011 - defaulted the most.
    - For customers with 'Mortgages home'; Funded Invoiced Amount, Number of Instalments, Rate of Interest, Loan Amount, Revolving Line Utilization Rate rapidly increased every year. Thus increasing the chances of rate of 'Defaults'

- Scenarios where loan was fully paid
    - In year 2007 customers with 'Highest Income' FULLY_PAID the loan in 'renewable energy' sector.
    - In year 2009 customers with 'Highest Income' FULLY_PAID the loan in 'renewable energy' sector.

- Customers with highest income lived in all types of homes.
    - Customer's Annual Income is highest where they have a 'mortgaged home' and loan application was verified.
    - Customer's Annual Income is highest where they have a 'Other home' and loan application was Source verified.
    - Customer's Annual Income is highest where they have a 'Own home' and loan application was verified.
    - Customer's Annual Income is highest where they have a 'Rented home' and loan application was verified.
 



## Conclusion & Recommendations
- Drivers for "Loan Default" and "not to Default"
- Who is NOT likely to Default?
    - Customers who 'FULLY_PAID' their loans are less likely to Default.

- Who is likely to Default?
    - "Grade": Customers with assigned Loan in "Grade B".
    - "Loan Amount": Customers whose loan fall in range of 6k-8k.
    - "House Ownership": Customers staying in Rented or Mortgaged home.
    - "Loan Term Period": Customers with average 3 years of loan term.
    - "Years of Experience": Customers with work experience of 10+ years.
    - "Loan Verification“: Customers whose loan application is 'not verified'

## Technologies Used
- Python
- Google Colab
- Jupyter Notebook
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scipy

## Acknowledgements
- https://www.youtube.com/watch?v=fiQhxn9RjEQ
- https://www.youtube.com/playlist?list=PLupD_xFct8mFDeCqoUAWZpUddeqmT28_L
- https://pandas.pydata.org/docs/user_guide/basics.html
- https://matplotlib.org/stable/tutorials/pyplot.html#sphx-glr-tutorials-pyplot-py
- https://seaborn.pydata.org/tutorial/introduction.html



## Contact
Created by [@dilipchauhan20] - feel free to contact me!


<!-- You don't have to include all sections - just the one's relevant to your project -->
