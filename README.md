# SEED (03.2020 ~ 02.2022)
* Society of Economics and Statistics at Ewha Womans University in South Korea
* For two semesters, I wroted two papers related to macroeconomics as the only statistician on two teams.

1. Project Introduction
   One of the two papers, "An Analysis of the Correlation between CD Interest Rates and Macroeconomic Variables: Using the VAR Model" started with a team paper and became our society's representative paper to be presented at the Korea-Japan University Association Seminar. 
   
2. Purpose of Analysis
    The paper aimed to determine the causes for the decline of the real economy despite a rapidly rising stock market due to oversupply created by COVID-19 stimulus.

3. Process of Analysis
   * Analysis Tools 
     <br/> R (libraries such as vars)
   * Data
     - variables representing investment demand
     - variables representing asset market
     - variables representing real economy
   * Analysis
     - Since all data was time series data, conducted the log difference of all variables based on the ADF unit root test
     - Selected VAR model based on the Johansen cointegration test and Granger causality test
     - Checked the reaction of variables representing asset market and real economy in response to CD interest rate by using impulse response function (IRF)

4. Result of Analysis
     CD interest rates had a significant effect on asset prices but had only a slight effect on the real economy.

5. What I learned
   * I took the initiative in the entire data analysis process, including problem identification, data collection and preprocessing, time series data modeling, visualization, and exploration.
   * I refined, analyzed and visualized data using R with libraries such as vars. 
