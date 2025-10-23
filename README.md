# Health-Economics projects
Excel-based Markov model simulating disease progression and evaluating treatment cost-effectiveness. Includes transition probability matrix, state costs and utilities, discounting, and ICER calculation for health economic evaluation.

# 🩺 Markov Model for Health Economic Evaluation (Excel)

This project builds a cohort-based Markov model in Microsoft Excel to simulate disease progression and evaluate the cost-effectiveness of a healthcare intervention.
The model applies key concepts from health economics and decision analysis, including transition probabilities, state costs, utilities, discounting, and incremental cost-effectiveness ratios (ICERs).

This work was inspired by online resources and adapted as a self-directed learning project to strengthen technical and analytical skills relevant to health economic modelling.

## Model Structure

Health States: Healthy → Sick → Dead

Cycle Length: 1 year

Number of Cycles: 36

Transition Probabilities: Defined via a 3×3 probability matrix

Population Updates: Calculated each cycle using Excel’s MMULT() function

Costs and Utilities: Assigned per health state and accumulated across cycles

Discounting: Applied at 3.5% annually to both costs and health outcomes


## Key Features

✅ Cohort simulation using matrix multiplication (MMULT)

✅ Annual cycle updates and population tracking

✅ Integration of cost, utility, and transition data

✅ Discounting of future outcomes

✅ Calculation of ICERs for comparative evaluation

✅ Visualization of Markov traces over time


## Learning Objectives

- Understand the structure and logic of Markov models in health economics.
- Gain experience building and testing decision models in Excel.
- Apply discounting and cost-effectiveness principles to model results.
- Interpret model outcomes and understand their implications for healthcare decision-making.

## Tools & Skills
- Microsoft Excel (matrix functions, data tables, visualization)
- Health Economics concepts (Markov models, cost-effectiveness, ICERs, discounting)
- Data analysis and interpretation
- Clear documentation and model transparency


References & Learning Resources

YouTube Tutorial: “Markov Models for Health Economic Evaluation in Excel” by Health Economics and Outcomes Research 
