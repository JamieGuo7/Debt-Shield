# Debt Shield

🛡️ DebtShield is a web-based platform linked to a browser extension that integrates directly into the checkout process. We built this during the Warwick Finance Societies Fintech Hackathon. 

## Heres how it works: 
- Users import their bank transaction data into a profile where we calculate income level, income volatility, recurring commitments, and spending behaviour.
- Using Monte Carlo simulation, we generate many possible 12-month cash flow paths and update monthly cash positions after income, expenses, interest, and required payments.
- A default event is defined as cash becoming negative at any point. The Shield Score is computed as the probability of remaining solvent across simulated paths.
- When a new purchase is initiated, the extension intervenes and recalculates this probability in real time, showing how the purchase changes financial stability and how it affects the time required to reach user-defined savings goals.

## What challenges did we have?
- Reliable price detection across diverse retailer web pages
- Seamless integration with different checkout architectures
- Presenting probabilistic risk information in a clear way
- Behaviourally effective without overwhelming the user
