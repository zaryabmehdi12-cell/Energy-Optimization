# optimization of a residential energy system 
**Modeling the Impact of User Behavior and Smart Technology using Linopy**

## Project Overview
This script uses linopy to model and optimize a residential energy system. It first calculates a baseline for annual energy cost and CO₂ emissions for a German household using grid electricity. It then solves a series of optimization problems to find the minimum cost of meeting the same energy demand by integrating solar PV under different scenarios, including smart home technology and behavioral interventions (nudges, real-time feedback). The final analysis compares each scenario's cost, emissions, and Return on Investment (ROI) to evaluate the effectiveness of each strategy.

Developed as part of the *Operations Research for Energy Systems Application* course at **Ruhr-Universität Bochum**.

## Instructors
- Dr. Jonas Finke  
- Viktor Schüßler  
- Jakob Niederhoff  

---

## Features
-Analyze average hourly electricity and heat demand (baseline).
- Calculate annual energy cost and CO₂ emissions.
- Optimize energy usage via:
  - Solar PV integration.
  - Smart home automation.
  - Behavioral nudging.
  - Real-time feedback from smart meters.
- Evaluate Return on Investment (ROI) for solar systems.
- Compare results across all scenarios.
---

## Technologies Used
- **Python 3.10+**
- **Linopy** – Linear optimization modeling  
- Pandas – Data handling  
- NumPy – Numerical arrays  
- Matplotlib – Plotting  

---

## Setup Instructions

1. **Clone the Repository**
```bash
git clone git@github.com:Linus-77/ORESA--Project-Energy-Optimization-.git
cd energy-linopy-project
