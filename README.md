# Project Title: Prosper Loan Analysis Using Python Libraries.
              This is a python analysis on Jupyter notebook using Numpy, Pandas, Seaborn and Matplotlib


### Data Source:
              This project belongs to a loan company called Prosper Loan.


### Project Description: 
               In this project, I took help from Numpy, Pandas, Seaborn and Matplotlib to create amazing visualizations.
               This project anaylzes the features in the dataset that will help me support my investigation into my features 
               of interest are: the Stated Monthly Income, Monthly Loan Payment, Prosper Loan Scores, the Loan status, 
               the Loan Original amount etc.. 
               This project reads prosper loan data
               from an Excel file, processes it, and then generates visualizations to analyze the data.
                     
### Execution: 
               In the course of this project, 
                     . I imported my Libraries: import pandas as pd
                                                import numpy as np
                                                import seaborn as sns
                                                import matplotlib.pyplot as plt
                                              
                     . Imported my dataset: car = df = pd.read_csv('Prosper Loan.csv')
                    
                     . Explored my dataset: my dataset has  81 columns and 113,937 rows.

                                            It also contains the following datatypes boolean (3), float (49), 
                                            int (12) and object (17).
                    
                     . Cleaned and Prepared my dataset: Dropped irrelevant columns, renaming the column names,
                                                        dropping duplicate rows and missing values etc.
                    
                     . Visualized my dataset: 
                                Some of the data visualized are:
                                       . Loan Months Since Origination Distribution
                                       . Loan Original Amount Distribution
                                       . Prosper Score Distribution
                                       . Prosper Rating (Alpha) Distribution
                                       . Is Borrower Home Owner By Income Range
                                       . Loan Original Amount By Income Range
                                       . Number of Investors By Loan Status
                                       . Loan Original Amount By Term

### Conclusion: 
              In conclusion, I observed that Income truely affects the amount of Loan individuals are been 
              granted in Prosper Loan Company because the more your Income, the more Loan you will be granted. 
              The less your income, the less loan you will be awarded.
              
              I also observed that the more investors you get to fund your Loan, the better chances your Loan 
              Status will be Completed but if you have less investors to fund your Loan, your Loan Status might 
              be Cancelled.
