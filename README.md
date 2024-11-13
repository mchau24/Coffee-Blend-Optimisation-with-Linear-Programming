# Cost Optimisation for a Coffee Blend using Linear Programming

## Overview
This project provides a linear programming model to design a cost-effective holiday coffee blend for an independent coffee shop. The blend incorporates four types of coffee beans to achieve a balanced flavour profile, optimising costs while meeting specific taste and aroma requirements.

## Problem Statement
The coffee shop aims to create a unique holiday blend using four coffee bean types:
- **Ethiopian Yirgacheffe (Y)** – floral, fruity
- **Colombian Supremo (S)** – nutty
- **Kenya Peaberry (P)** – earthy, fruity
- **Guatemalan Huehuetenango (H)** – chocolatey, citrusy

## Model Details
### Objective
Minimise the cost per 100g of the blend, meeting the shop’s specified flavour profile.

### Decision Variables
- Proportions of each coffee bean in the blend.

### Constraints
1. Total proportion of all beans equals 1.
2. High level of acidity.
3. Medium level of strength.
4. Floral and fruity notes (Y and P) contribute at least 40% of the aroma.
5. Nutty notes (S) limited to a maximum of 20%.

### Solution and Analysis
Using linear programming (Excel Solver), the optimal blend consists of:
- **Supremo**: 11.8%
- **Peaberry**: 82.3%
- **Guatemalan**: 5.9%
  
The Yirgacheffe bean is omitted from the optimal blend due to cost, although floral notes are desirable.

### Sensitivity Analysis
Further insights from the sensitivity analysis include:
- Reduced cost for Yirgacheffe indicates potential for inclusion if its price decreases by ~9.4%.
- Shadow prices suggest increasing acidity may enhance blend quality, while adjustments to the strength level have minimal impact on cost.
