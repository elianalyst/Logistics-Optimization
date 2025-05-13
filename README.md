# 🚛 Logistics Optimization for Delivery Network Efficiency

## Project Overview
This project analyzes and optimizes a delivery logistics network using multi-objective optimization modeling. The analysis aims to minimize shipping costs while also reducing delivery times, improving profitability and customer satisfaction. The study models constraints related to truck capacity, delivery routes, and shipping center limitations.

**Research Question**: How can a logistics company minimize costs and improve delivery efficiency through optimization modeling?

## Methodology
- Linear Programming was used to minimize operational costs involving fuel, labor, and truck maintenance.
- Nonlinear Optimization techniques were applied to delivery time constraints involving variable factors like traffic and route scheduling.
- A weighted sum method was used to balance cost and time goals in a multi-objective optimization framework.

## Key Findings
- A Pareto-optimal solution set revealed trade-offs between cost savings and delivery speed.
- The optimized network met all constraints, ensuring efficient, reliable fulfillment.
- Only 67 of 191 shipping routes were used, highlighting opportunities to streamline operations.
- Hyderabad and San Bernardino focus centers were bypassed in the optimal network — indicating they are not essential for cost-effective fulfillment and could be decommissioned or repurposed to reduce facility and labor expenses.
 
## Technologies Used
- Python
- PuLP (linear programming)
- SciPy.optimize (nonlinear optimization)

## Full Report
To explore the optimization model, equations, and final recommendations, check out the full [Logistics Optimization.ipynb](./Logistics%20Optimization.ipynb) notebook.