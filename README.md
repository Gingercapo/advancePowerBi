# AdvancePowerBi

## Loan Financial Model
 
- I worked on  Loan Financial Model with regard to interest rate and Mortage rate calculations, effectively leverage the DAX language to create advanced queries, and used the M language to improve the querying process.
 
- I demonstrates how to get data into Power BI using the Power Query editor and then model the loaded data using DAX columns, tables, and measures. To lend these concepts in real-world context, I created a financial model for loans.
- <img src="https://user-images.githubusercontent.com/56441231/200066043-5a915600-fb8f-48c1-9354-40c78ba90dcd.png" width="600" height="300" />
   
 At time zero, we borrow a given amount of money. We then agree to pay back the loan in payments over a given time period. Like in this case, we have five years.
    
- For our model, we're going to say the loan payments are even and pay is done at a regular cadence. If we compare the total loan payments to the total loan amount taken out at time zero, the total payments are higher. 
    
- This is because when we make payments, we're not only paying back the principal of the loan we took out at the beginning, but also the interest on this loan, which we can use the 15-year and 30-year average rates to determine what the loan interest will be.

- The interest paid isn't the same for each payment period though, but rather it decreases over time as the loan balance decreases over the duration of the life of the loan. 

- This subsequently means, we're paying more of the payment toward the principal as we progress through the life of the loan. Some of the key calculations we'll do in the loan model include converting an annual interest rate into a monthly one, 

- where i represents the annual interest rate. The level payment amount. The loan balance at each period in the loan. The interest paid for each period. And the principal paid for each period. To keep track of the DAX formulas, I'm also going to number them for the individual tables for Model 1 and Model 2.

- Because the order of fields in Power BI gets alphabetized by text characters starting at zero, i will  then denote the order of the measures calculated within each model using the sequence zero-one zero-two and so on as we build out the loan models in Power BI.






