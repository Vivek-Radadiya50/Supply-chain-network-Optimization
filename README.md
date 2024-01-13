1. **Problem Overview:**
   - The project aims to optimize a supply chain network, minimizing the total cost of fulfilling customer demand.
  
2. **Network Structure:**
   - Involves 5 suppliers providing 4 types of raw materials to 3 factories, producing 4 types of products for 4 customers.

3. **Data Provided:**
   - Information on supplier stock, raw material costs, shipping costs, required raw materials, production capacities, production costs, customer demands, and shipping costs of final products.

4. **Assumptions:**
   - Weekly demand and stock consideration.
   - Ignored lead time, assumed instant deliveries.
   - Manufacturing time and product sizes are not considered.

5. **Solution Methodology:**
   - Utilizes ortools to minimize the total cost, including raw material purchasing, transportation, production, and final product transportation costs. The model is formulated with decision variables, constants, and an objective function, subject to specific constraints.
