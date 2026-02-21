# Telecom Revenue Analysis: Surf vs Ultimate

## Objective

Determine which prepaid plan generates higher revenue using customer-level usage data and statistical testing.

## Data

500 customers during 2018.  
Monthly call minutes, text messages, internet usage, plan type, and billing information.

## Approach

- Aggregate usage at the user-month level  
- Compute monthly revenue based on plan pricing rules  
- Compare average revenue using hypothesis testing  
- Evaluate total annual revenue by plan  

## Results

- Call usage is similar across plans.  
- Ultimate users consume more data and send more messages.  
- Average monthly revenue per user is significantly higher under Ultimate at the 0.01 significance level.  
- Total annual revenue is higher for Surf: 95,491 USD versus 52,066 USD.  

## Conclusion

Ultimate generates higher revenue per user.  
Surf generates higher total revenue due to its larger customer base.

## Tools

Python, Pandas, NumPy, Matplotlib, SciPy