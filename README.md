# Overview

In this hands-on activity, you will step into the role of a financial analyst responsible for managing a client’s investment portfolio. Your task is to calculate portfolio values, returns, and other key metrics using Excel's arithmetic operators and functions. Through this activity, you'll understand how to perform basic financial calculations, apply the BODMAS rule, and use Excel’s built-in functions to analyze and manage the portfolio effectively.

#Objective 
 - understand and use basic arithmetic operators (+, -, *, /) in Excel for calculations

 - apply the BODMAS (Brackets, Orders, Division/Multiplication, Addition/Subtraction) rule in Excel formulas

- use common mathematical functions such as SUM, AVERAGE, MIN, MAX, and COUNT to analyze data

- calculate the performance of an investment portfolio, including returns and overall portfolio value

 Required tools
Tool 1: Microsoft 365 with Copilot

Tool 2: Access to a sample dataset:

Activity description
Scenario
You are a financial analyst tasked with managing the investment portfolio of a client. The portfolio contains different assets like stocks, bonds, and mutual funds, with each having varying returns over the past year. Your client wants to know the overall performance of their portfolio, including the total value of investments, average returns, the highest and lowest returns, and the number of assets in their portfolio.

Your primary task is to use Excel to calculate and analyze this data, ensuring accurate results that can be shared with your client. You’ll also use BODMAS to ensure that complex calculations are performed correctly. In addition, you’ll use built-in Excel functions like SUM, AVERAGE, MIN, MAX, and COUNT to streamline your analysis.

Step-by-step instructions
Follow the set of steps that will give guidance in training a predictive model.

Task 1: Explore basic arithmetic operators
Download the Investment portfolio dataset that is available in the Required Tools section. 

Open the Excel file and review the columns, which include Investment Name, Investment Cost, Number of shares owned, Total shares, and Fair Market Value.

Calculate the monetary Return on Investment (ROI) for each investment using the following steps:

Start by calculating your percentage ownership of each investment using the division (/) operator.

 Apply this percentage ownership to the Total Fair Market Value of each investment to calculate what each investment is worth (i.e. your share of the Fair Market Value) by using the multiplication (*) operator.  

Finally, to calculate the return on each investment, subtract your Initial Investment Cost from your share of the Fair Market Value using the subtraction (-) operator.

Now calculate the % ROI on each investment by prompting Copilot to generate this formula for you. Insert the additional column at the end of the dataset.

Task 2: Apply the BODMAS rule
For a more complex scenario, assume you need to apply fees and taxes on the annual returns.

Use the assumption that you need to pay 15% tax on the return you’ve earned on each investment as well as a fixed administration fee of €100 per investment, and calculate the net fair market value of each investment. For example:

Initial Investment Cost: €1.000.000

Your share of the FMV: €1.500.000

Therefore the return on this investment: € 500.000 = (€1.500.000 - €1.000.000) 

Now calculate the tax due on the return: €75.000 = (€500.000 * 15%)

Don’t forget to subtract the fixed administration fee of €100 as well

Using BODMAS, you can create one formula to calculate the net Fair Market Value

Net Fair Market Value: €424.900 = (€500.000 – (€500.000 * 15%) - €100)

Apply BODMAS to ensure the correct calculation of returns after deductions. Use brackets to prioritize operations and subtract the fees and taxes after calculating the returns.

Task 3: Use mathematical functions (SUM, AVERAGE, MIN, MAX, COUNT)
You can practice the mathematical functions manually or using Copilot. 

Calculate the Total Investment Cost:

Use the SUM function to calculate the total amount invested across all assets

Or prompt Copilot to calculate the Total Investment Cost across all assets

Find the Average Return:

Use the AVERAGE function to calculate:

the average return on all investments in €

the average % return on all investments

Or prompt Copilot to find the Average Return and the average % return on all investments.

Use the MIN and MAX functions to find:

Find the minimum and maximum returns:

The lowest and highest Initial Investment Cost

The lowest and highest ROI %

Or prompt  Copilot to find the minimum and maximum returns

Count the Number of Investments: 

Use the COUNT function to determine how many investments are in the portfolio

Or prompt Copilot to find the minimum and maximum returns.

Task 4: Analyze portfolio performance
Identify which investments are underperforming and which ones are providing high returns using Copilot. Hint: prompt Copilot to apply conditional formatting to highlight the investments with high returns and the underperforming investments in a different color.

Prompt Copilot to identify outliers in your investment portfolio.

Task 5: Visualize the data

Create a simple bar chart or line graph to visualize the return rates (%) for each investment.
