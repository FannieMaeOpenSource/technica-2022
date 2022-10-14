# technica-2022

## Technica Challenge Description

Understanding what it takes to purchase a home has always been challenging. The paperwork can be extremely confusing and dense, and it is hard to figure out if you have the necessary means to complete the purchase. What steps can you take to improve your ability to purchase a home?

In this challenge we are presenting you with a list of potential homebuyers and some relevant data for each of them. The goal of this challenge is two-fold.

1.  Evaluate the potential homebuyer data and determine if they are ready to buy a home.

2.  If they are not – offer meaningful suggestions about steps that they can take to improve their position.

The data and decision factors we are presenting here represent a simplified version of the information and how the process works in the real world, however the data represents some of the real-world factors or information used to make home buying eligibility decisions. 

Please note: The data is completely mocked up and does not include any actual buyer information from any source. 

If you accept this challenge - begin by reviewing the decision criteria and examining the data. Then mock-up your program by talking about the various aspects your code will have to handle. For example, reading in the associated data files, looping through the relevant records, applying the decision criteria (if-then statements for example), and determining if the potential homebuyer is ready or if not - what factors they need to improve. 

You could first create a process to analyze the data we have provided but then go on to create a GUI (Graphical User Interface) that allows you to type in information about potential homebuyers of your own. 

## The Process and Approval Factors

A potential buyer should be approved for a home purchase if all these conditions apply: 

- Credit rating is 640 or above 

- LTV (loan-to-value) is < 80% is preferred, between 80% and 95% could lead to higher interest rates and require the purchase of mortgage insurance. For example, suppose you buy a house that appraises for $100,000. If you make a $20,000 down payment your loan will be $80,000 which results in an LTV ratio of 80%. If you increase your down payment to $25,000 your LTV will be 75%. On the other hand - if you put down $10,000 your LTV will be 90%. You might still qualify for the home, but you would have to purchase Private Mortgage Insurance (PMI) which will add to the amount you will pay for the house. If PMI charges 1% of the house price that will be an additional $1000 per year ($83.33 per month) that you would have to pay for your house. Typically, but not always, PMI is required until the LTV drops below 80%. 

- DTI (Debt-to-income ratio) is the percentage of your gross monthly income that goes to paying your monthly debt payments and is used by lenders to determine your lending risk. Typically, the highest DTI a lender will accept is 43% but in general lenders prefer ratios of not more than 36% with no more than 28% of that debt going towards servicing a mortgage. One way to lower your DTI score would be to transfer high interest loans to a low interest credit card although having too many credit cards can also negatively impact your ability to purchase a home. For example, DTI can be calculated as follows:

Monthly Debt -> $460 + $500 + $1200 = $2160
- Gross income -> $5000 per month
- Car Payment -> $460 per month
- Credit Card Payments -> $500 per month
- Mortgage -> $1200 per month
- DTI -> $2160 / $5000 = 43%|

- A “Front-end debt to income” (FEDTI) ratio less than or equal to 28%. This ratio represents your total monthly debt from housing expenses alone divided by your gross monthly income. Using the same data from above – monthly mortgage payment of $1200 / gross income of $5000 yields 24% FEDTI.

- Your app will have to calculate results for LTV, DTI, and FEDTI and then make the appropriate decisions based on those values. 

If the potential homebuyer does not meet the necessary criteria to purchase a home, you should evaluate several factors and provide one or more suggestions that will help improve the buyer's opportunity to buy a home in the future. These suggestions could include: 

- Pay off some current debt

- Transfer debt to a lower interest rate loan / credit card 

- Look for a less expensive home 

- Increase your down payment amount 

- Continue renting while saving more for a down payment 

## The Data

Attributes included in the data file are as follows:

- ID
- Gross Monthly Income
- Monthly Car Payment
- Monthly Credit Card Payment
- Student Loan Payment
- Home Appraised Value
- Est. Monthly Mortgage Payment
- Down Payment amount
- Credit Score

 
## Ideas and Suggestions

- Write a program to process the batch file and post Y for Approved or N for not approved 

- Collect metrics along the way that keep track of approved or not and WHY they were not approved. 

- Generate a graph displaying the %’age of approvals / non-approvals broken down by the deciding factor(s) that led to not approving the requested loan 

- Create a GUI that allows you to enter your own made-up potential home buyer’s and property information and see how your code rates them 

- Augment the GUI to have slider bars for each of the relevant attributes (Appraised value, Down Payment, etc.) and display the resulting approval / non-approval decision 

- Create an output file of results and email it

- Provide links to relevant articles / ways to improve a buyer’s eligibility based on where they might currently fall short

Above all – please remember to have fun with this challenge – take the opportunity to do some internet searching for more information about the home buying process and what you can do to help improve your ability to purchase a home. Learn how to create graphs or other types of visualizations to help display key results.  

https://github.com/FannieMaeOpenSource/technica-2022

 
