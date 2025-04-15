# Excel-Solver-application-in-Supplier-selection
Application of Excel Solver for optimizing the Supplier selection process (ERX Procurement case)
1. Objective
This project aims to determine the optimal procurement plan for medical masks (indirect materials) for four training centers (Ho Chi Minh, Ha Noi, Hai Phong, and Đa Nang) operated by ERX Vietnam. The goal is to minimize the total procurement cost while satisfying demand in each centers and supplier capacity.
2. Tools used
Two tools were used for analysis and optimization:
Microsoft Excel: Used for data input, cost structuring, and visual presentation of supplier bids.
Solver Tool (in Excel): Applied for solving linear programming problems to find the optimal order quantity under given constraints (Using both Nonlinear GRP and Evolutionary method)
3.  Process
3.1 Understanding the procurement problem
Four training centers demand a specific quantity of masks.
Multiple suppliers offer different quotation depending on the delivery location.
The masks are purchased in units of 1,000 per box.

3.2 Steps for optimization
Step 1: Input supplier price matrix for each logistics center.
Step 2: Define constraints such as total demand per center and supplier-specific conditions (e.g., minimum orders).
Step 3: Use Excel Solver to minimize the total cost under these constraints.

3.3 Progressive constraints by sheet
Question 1.1: Basic demand satisfaction at each center.
Question 1.2: Adds a minimum order constraint for Supplier 1.
Question 1.3: Alters the constraint to focus on Supplier 2.
Question 1.4: Combines constraints on both Supplier 1 and Supplier 2 for a more realistic procurement strategy.
4. Key findings
Sheet: Question 1.1
Solver distributes purchases across suppliers to fulfill demand at the lowest cost.
Without additional constraints, the solution often favors the lowest bidder per location.
Sheet: Question 1.2
Imposing a minimum purchase volume for Supplier 1 shifts part of the order to meet this requirement, even if not the cheapest option.
Sheet: Question 1.3
A similar effect is seen when Supplier 2 has a required minimum volume, demonstrating how supplier terms influence procurement decisions.
Sheet: Question 1.4
Balancing constraints across multiple suppliers leads to a more complex, but feasible and cost-effective distribution plan.
Highlights the trade-off between cost efficiency and supplier commitment.
