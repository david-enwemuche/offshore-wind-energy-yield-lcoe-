# Offshore Wind Energy Yield & LCOE Model
A Python-based engineering analysis project for assessing offshore wind resources, turbine energy production and project level economics.

## Project Overview
This project demonstrates a Python-based workflow for analysing illustrative offshore wind energy yield and estimating the levelised cost of energy (LCOE).

The model uses a simplified 15 MW offshore wind turbine and illustrative project assumptions. It brings together energy-yield calculations, performance indicators, discounted cost calculations and sensitivity analysis.

The project was developed to demonstrate practical analytical skills and explore how engineering performance and cost assumptions influence the assessment of renewable energy projects.

## Key results
|**Metric** | **Illustrative result**|
|---|---|
|Net annual energy production | 23.325 GWh/year|
|Net capacity factor | 17.75%|
|Net equivalent full-load hours | 1,555 hours/year|
|Baseline LCOE | £275.16/MWh|
|Project life | 25 years|
|Discount rate | 8%|
|Capital expenditure (CAPEX) | £52.5 million|
|Annual operating expenditure (OPEX) | £1.5 million|

These results are based on simplified assumptions and are not forecasts for an actual offshore wind farm.

## CAPEX sensitivity analysis
The following scenarios illustrate how the estimated LCOE changes with capital expenditure.

**CAPEX (£m/MW)** |	**LCOE (£/MWh)**
|---|---|
2.5 |	214.92
3.0 |	245.04
3.5 |	275.16
4.0 |	305.28
4.5 |	335.40


## OPEX sensitivity analysis
**Annual OPEX (£m/year)** |	**LCOE (£/MWh)**
|---|---|
1.00 |	253.72
1.25 |	264.44
1.50 |	275.16
1.75 |	285.88
2.00 |	296.60

The results show that the estimated LCOE increases as capital and operating costs rise, highlighting the value of sensitivity analysis when comparing project assumptions.


## Tools
    -Python
    -Pandas and Numpy
    -Matplotlib
    -Jupyter Notebook
    -Energy-yield and capacity-factor calculations
    -Discounted cost and discounted energy calculations
    -CAPEX and OPEX sensitivity analysis


## How to run the project
Install the required libraries:

pip install -r requirements.txt
Launch Jupyter Notebook:

jupyter notebook
Open notebooks/offshore_wind_energy_yield_lcoe.ipynb and run the cells from beginning to end.

## Assumptions and limitations
This is an illustrative portfolio project using simplified assumptions. It is not a bankable feasibility study or an independently validated assessment of a specific offshore wind site.

The model does not replace a detailed wind-resource assessment, wake modelling, site-specific loss analysis, uncertainty assessment or a complete project-financing model. Results depend on the assumptions and the cost and energy boundaries used in the notebook.

## Author
David Enwemuche

Inverness, Scotland
Email: enwemuchedavid@gmail.com
LinkedIn: https://www.linkedin.com/in/david-enwemuche-34b6171b2
