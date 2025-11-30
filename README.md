# ⚡ U.S. Energy Mix Optimization – Multi-Objective Decision Model

---
## Files

**Full Report (PDF):**  
[View Presentation](https://github.com/Timothy0324/Optimizing-the-U.S.-Energy-Mix/blob/main/ADT_Presentation(Azure%2C%20Revati%2C%20Timothy).pdf)

**Excel-Based Model:**  
[Open Excel](https://github.com/Timothy0324/Optimizing-the-U.S.-Energy-Mix/blob/main/ADT_Final%20Project_Liu%2C%20Hsiao%2C%20Wankhede.xlsx)

---

## Project Overview

This was a final team project for the course **Advanced Decision Technology** at the University of Pittsburgh.  
Our goal was to model a realistic national energy planning problem using linear programming and multi-objective analysis.

We created an Excel-based tool that:
- Models generation decisions under strict constraints (emissions cap, demand, and capacity)
- Explores trade-offs between **minimum cost** and **maximum reliability**
- Visualizes Pareto-optimal outcomes to support informed policymaking

We presented our findings using slides that included:
- Problem framing and methodology  
- Key insights from scenario modeling  
- Final recommendations and a phased action plan

This project demonstrates both **quantitative modeling skills** and the ability to **translate data into real-world decisions**.

---

## Problem Statement

> The U.S. must meet growing electricity demand while navigating strict CO₂ caps, fluctuating fuel prices, and pressure to phase out fossil fuels.

**Goal:**  
Find the best energy mix that:
- Minimizes total cost  
- Maximizes overall reliability  
- Stays under a strict **100 metric ton/year CO₂ emissions cap**  
- Respects source capacity limits  

---

## Methodology

We used a **Pareto-based decision model** to evaluate trade-offs between cost and reliability. The model explores multiple scenarios to generate a **set of non-dominated solutions**, not just a single “best” answer.

| Metric       | Description |
|--------------|-------------|
| Min Cost   | $48,200 (but only 45% reliability) |
| Max Reliability | 66% (but higher cost: $63,300) |
| Pareto Points | Balanced options between cost and reliability |

**Constraints:**  
- Emissions ≤ 100 metric tons CO₂/year  
- Total generation = 1000 MWh  
- Generation capacity limits for each source

<img width="874" height="329" alt="image" src="https://github.com/user-attachments/assets/2d2126fc-8128-496a-9700-e82ea7b34468" />


---

## Key Insights

- Current emissions cap holds reliability at just **66%**, below the 90% benchmark  
- Fossil fuels are cheap and reliable, but CO₂-limited  
- Nuclear is clean and reliable, but capacity-constrained  
- Trade-offs are inevitable — but modeling helps make them transparent and data-driven

---

## Final Recommendations

1. **Raise the CO₂ cap slightly** to allow more fossil generation and improve reliability  
2. **Increase the nuclear generation ceiling** to expand zero-carbon, firm capacity  
3. **Invest in clean-firm technologies** like long-duration storage and demand response  
4. **Use a cloud-based planning tool** to re-optimize the mix quarterly as prices, policies, and technologies change

---

## Next Steps

| Phase | Action |
|-------|--------|
| Policy Analysis | Reassess the CO₂ cap based on system reliability needs |
| Nuclear Roadmap | Explore uprates or SMRs to raise the 300 MWh limit |
| Clean-Firm Pilots | Test long-duration storage and demand response |
| Tool Roll-Out | Launch a cloud-based re-optimisation platform for DOE/EIA |

---

## Team

**Timothy Liu** – MS in Marketing Science & Business Analytics  
**Azure Hsiao** – MS in Marketing Science & Business Analytics  
**Revati Wankhede** – MS in Management & Business Analytics  
University of Pittsburgh | Katz Graduate School of Business  
Project Advisor: Prof. Elena Rokou
