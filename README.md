# OPTIMIZATION-MODEL

*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : MAYANK SHARMA

*INTERN ID* : CT04DZ2045

*DOMAIN* : DATA SCIENCE

*DURATION* : 4 WEEKS

*MENTOR* : NEELA SANTOSH

## Description of the Task:

This task involves applying optimization techniques, specifically linear programming (LP), to solve a practical business problem using Python and the PuLP library. The goal is to demonstrate how mathematical modeling and computational tools can be used to make data-driven decisions that maximize profitability under resource constraints.

Business Context:
Imagine a manufacturing company that produces two products—Product A and Product B. Each product requires a certain amount of labor hours and raw materials to produce. The company has limited resources: a fixed number of labor hours and a limited supply of materials. Additionally, each product contributes differently to the company’s profit. The challenge is to determine the optimal number of units of each product to produce in order to maximize total profit, without exceeding the available resources.

This type of problem is common in operations research and supply chain management, where businesses must allocate limited resources efficiently. Linear programming provides a powerful framework for modeling such problems and finding optimal solutions.

Mathematical Formulation:
The problem is formulated as a linear programming model with the following components:

Decision Variables:

𝑥 : number of units of Product A to produce

𝑦 : number of units of Product B to produce

Objective Function:
Maximize profit: 20𝑥 + 30𝑦

Product A yields $20 profit per unit
Product B yields $30 profit per unit

Constraints:
Labor Constraint: 2𝑥 + 3𝑦 ≤ 100

Product A requires 2 hours of labor
Product B requires 3 hours of labor

Total labor available: 100 hours

Material Constraint: 4𝑥 + 2𝑦 ≤ 80

Product A uses 4 units of material
Product B uses 2 units of material

Total material available: 80 units

The model is solved using the PuLP library, which provides a user-friendly interface for defining LP problems and invoking solvers.

Implementation in Python:
The task is implemented in a Python notebook. After importing the necessary components from PuLP, the model is defined, constraints are added, and the solver is invoked. The output provides the optimal values for the decision variables and the maximum profit.

Results and Insights:
The solution indicates that the optimal strategy is to produce 0 units of Product A and 33.33 units of Product B, resulting in a maximum profit of $1000. This outcome suggests that Product B is more profitable relative to its resource consumption. Labor is fully utilized (100 hours), while some material remains unused (only 66.66 units consumed out of 80).

This result provides valuable business insights:

Product B should be prioritized in production planning.

Product A may need reevaluation—either its cost structure, pricing, or strategic importance.



The company could consider adding constraints to ensure a minimum production of Product A if it serves other business goals (e.g., market presence or customer retention).
