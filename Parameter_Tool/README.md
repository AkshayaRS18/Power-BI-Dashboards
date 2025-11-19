### Workout Wednesday Challenges Challenge 1: Using Parameters in Power BI

**Focus:** Numeric Field Parameters & Field Parameters for Dynamic Visuals

In this challenge, I experimented with **Power BI Parameters** to make visuals more interactive and insightful.

#### (1) Numeric Field Parameter

Used a **numeric field parameter** to dynamically display different **data labels** in an *Inventory Value Trend* chart.
This allows the viewer to switch between metrics (e.g., inventory value, stockouts, holding cost, etc.) and see the corresponding label update instantly.

#### (2) Field Parameter (Y-Axis Selection)

Implemented a **field parameter** to let users dynamically choose which metric appears on the **Y-axis**.
For example, based on *Part Category*, users can toggle between:

* Inventory Value
* Stockout Incident Count
* Average Holding Cost
* Inventory Volume
  (over the 12 months of 2024)

#### (3) Field Parameter (X-Axis Selection)

Another field parameter was added to toggle the **X-axis** between:

* Part Category
* Month-Year

This creates a flexible and highly customizable trend view for business users.
