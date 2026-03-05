# 🛡️ DebtShield
> **Winner: Best Overall Hack** & **Best Financial Inclusion** @ *Warwick Finance Societies Fintech Hackathon (2026)*

DebtShield is a web-based platform linked to a browser extension that integrates directly into the checkout process. This is designed to bridge the gap between impulsive spending and long-term financial health and targets at-risk users with rising debts. We built this during the Warwick Finance Societies Fintech Hackathon. 

## 🏆 Achievements
* **Best Overall Hack:** Awarded for excellence across technical execution, innovation, impact, and functionality.
* **Best Financial Inclusion Hack:** Recognised for helping users with money management problems better manage their finances.

---

## 💡 The Problem
Modern e-commerce is designed to be frictionless, making it dangerously easy to spend impulsively without understanding the long-term effects. At the point of sale, customers only see their current balance, and not how it affects their cashflow in the future. For those with rising debts or volatile income, a series of small, impulsive decisions creates debt avalauche which we aim to avoid by providing better visibility and intervening when required.

## 🛠️ How It Works
DebtShield moves beyond static budgeting by using probabilistic forecasting:

1.  **Data Ingestion:** Users import transaction history into a profile where we calculate income level, income volatility, recurring commitments, and spending behaviour.
2.  **Stochastic Modeling:** We run a **Monte Carlo simulation** to generate thousands of possible 12-month cash flow paths.
    * Variables include income timing, expense spikes, and interest rate fluctuations.
3.  **The Shield Score:** We define a "Default Event" as any point where projected cash becomes negative. The **Shield Score** represents the probability of remaining solvent across all simulated paths.
4.  **Real-Time Intervention:** Our browser extension detects the "Total" at checkout. It instantly re-runs the simulation to show how that specific purchase drops your Shield Score and how many days/weeks it adds to your user-defined savings goals.

---

## 🏗️ What challenges did we have?
1. Reliable price detection across diverse retailer web pages
2. Seamless integration with different checkout architectures
3. Presenting probabilistic risk information in a clear way
4. Designing DebtSheild to be behaviourally effective without overwhelming the user
   
---

## 🚀 Future Roadmap
* **Open Banking Integration:** Moving from manual data imports to real-time API syncing via Plaid or TrueLayer.
* **Smart Alternatives:** Suggesting lower-cost alternatives or "Wait 24 Hours" cooling-off periods for high-impact purchases.
* **Advanced Goal Tracking:** Integrating "Buy Now, Pay Later" (BNPL) debt-trap detection.
  
---

## 👥 The Team
This project was built in 24 hours by:
* **[Shubhdeep Khasriya](https://github.com/ShubhdeepK)**
* **[Jamie Guo](https://github.com/JamieGuo7)**
* **[Daiki Asano](https://github.com/daiki078)**
* **[Will Bradbury](https://github.com/wbradbury1)**
