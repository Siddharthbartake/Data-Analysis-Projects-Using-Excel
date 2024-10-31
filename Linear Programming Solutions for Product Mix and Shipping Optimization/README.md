
# Optimization Analysis for Product Mix and Distribution Cost Minimization: Solutions for Better Products, Inc. & Happy Toys LLC

### Overview
This README file details solutions to the two optimization problems provided. The goal of these problems was to use Excel Solver to derive optimal solutions for a manufacturing and distribution scenario. Key results, tables, and recommendations are summarized below.

---

### Problem 1: Better Products, Inc.

**Objective**: Determine the optimal product mix to maximize weekly profits, given the constraints on machine hours, labor hours, and production requirements.

#### Constraints and Requirements:
- **Available Hours**: Each machine has 36 hours available per week.
- **Labor Hours**: 148 labor hours are allocated per week.
- **Production Requirements**:
  - Product 1 must account for at least 40% of the total units produced.
  - Product 2 production should not exceed 25% of the combined production of products 1 and 3.
  
#### Solution Summary:
- **Optimal Product Mix**:
  Using Excel Solver, we identified the ideal quantities for each product to maximize profit while satisfying all constraints.
  
- **Weekly Profit**: Projected profit based on the optimal product mix is calculated in the Answer Report.

- **Machine and Labor Analysis**:
  From the results, machine hours and labor hours used were reviewed. Increasing labor capacity would likely yield the most significant improvement in production, as indicated in the sensitivity report.

- **Additional Findings**:
  - **Value of Additional Labor**: The sensitivity report shows that additional labor hours would positively impact profit by a specific marginal value.
  - **Recommendation**: Increase labor by the feasible margin highlighted in the sensitivity report to optimize production further.

| Category       | Product 1 | Product 2 | Product 3 |
|----------------|-----------|-----------|-----------|
| Profit/unit    | $30       | $50       | $35       |
| Machine 1 (hr) | 1.25      | 1.75      | 1.00      |
| Machine 2 (hr) | 1.0       | 1.0       | 0.75      |
| Machine 3 (hr) | 0.75      | 0.75      | 1.25      |

---

### Problem 2: Happy Toys LLC

**Objective**: Minimize shipping costs for distributing products from three centers (William Lakes, Kamloops, Revelstoke) to various cities, considering demand and capacity limits.

#### Constraints:
- **Capacity**:
  - William Lakes: 12,100 units
  - Kamloops: 9,000 units
  - Revelstoke: 10,000 units
- **Demand**: Minimum demand per city must be met, as determined from the average monthly sales.

#### Solution Summary:
- **Total Shipping Cost**:
  Solver provided an optimal distribution plan minimizing shipping costs while meeting all constraints.
  
- **Distribution Recommendations**:
  Based on shipping costs and center capacity, expanding specific centers, particularly Kamloops, could reduce costs further. 

| City           | William Lakes ($) | Kamloops ($) | Revelstoke ($) |
|----------------|-------------------|--------------|----------------|
| Abbotsford     | 10.25             | 5.25         | 6.00           |
| Burnaby        | 9.75              | 4.25         | 5.25           |
| Campbell River | 8.25              | 6.25         | 8.75           |
| Coquitlam      | 9.50              | 4.00         | 5.00           |
| Courtenay      | 8.25              | 6.25         | 8.75           |

#### Key Findings:
- **Shipping Cost Minimization**: The model achieves significant cost savings by favoring lower-cost centers for specific cities.
- **Capacity Expansion**: Kamloops is recommended for expansion due to its central location and cost-effectiveness.

---

**Note**: For detailed data and Solver configurations, refer to the Answer and Sensitivity Reports in each Excel file.
