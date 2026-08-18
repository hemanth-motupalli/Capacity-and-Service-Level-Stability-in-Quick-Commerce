# Capacity and Service-Level Stability in Quick Commerce Delivery Networks

## Overview
Quick commerce platforms operate under strict 10–20 minute delivery commitments, creating intense pressure on logistics capacity and fulfillment operations. This project develops a **System Dynamics (SD) model** to examine how demand variability, rider availability, picking constraints, and inventory replenishment delays dynamically interact to influence delivery performance over time.

## Key System Dynamics Modeled
The model represents a simplified quick-commerce dark store system mapped via Stock-and-Flow Diagrams (SFD) and Causal Loop Diagrams (CLD). It captures several interacting balancing and reinforcing feedback loops:
* **Demand-Service Stabilization Loop:** How rising backlogs increase delivery delays, thereby moderating future order arrivals.
* **Workforce Adjustment Loop:** How capacity utilization triggers hiring rates and onboarding delays.
* **Inventory-Fulfillment Constraint Loop:** How limited stock restricts the order fulfillment rate and slows backlog clearance.
* **Workforce Attrition Loop:** The impact of rider turnover on maintaining baseline delivery capacity.

## Scenarios Analyzed
The system was stress-tested against several real-world operational challenges:
1. **Demand Surge:** Simulating sudden spikes (e.g., festive sales, heavy rainfall) leading to system congestion and degraded service levels.
2. **Peak Demand with Recovery:** Modeling intra-day cyclical demand patterns.
3. **Flexible Workforce Policy:** Implementing gig-based surge capacity to dynamically adjust to peaks, significantly reducing backlog oscillations.
4. **Workforce Attrition (High Work Pressure):** Simulating capacity crashes due to increased rider exits.

## Tech Stack
* **Modeling Methodology:** System Dynamics
* **Software:** Vensim

## Team: System Thinker
* **Motupalli Hemanth Kumar** 
* **Ashish Shukla**
* **Bhupesh Ranjan Jha**
