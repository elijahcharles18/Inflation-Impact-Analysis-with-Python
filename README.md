# Inflation Impact Analysis with Python

## Overview
Inflation occurs when there is a sustained increase in the general price level of goods and services in an economy over time. It impacts various aspects of the economy, including purchasing power,consumer behaviour, savings and investment. Moderate inflation is typically a sign of healthy, growing economy, as it encouraes spending and investment. However, high or unpredictable inflation can erode the value of money, disrupt financial planing, and lead to economic uncertainty. To analyze the impact of inflation, we need to compare it with the exchange rates over time. This comparison is important because exchange rates are influenced by inflation differentials between countries, such that higher inflation in a country generally leads to a weaker currency relative to countries with lower. The dataset used for this task contains inflation and exchange rates in Nigeria and United States over time.

## Features
- **Data Import and Cleaning**: Reads and preprocesses data for analysis.
- **Exploratory Data Analysis (EDA)**: Examines inflation trends and their correlations with other variables.
- **Data Visualization**: Generates clear and insightful plots to communicate findings.
- **Statistical Analysis**: Implements statistical methods to quantify the impact of inflation.
- **Reproducible Research**: Uses Jupyter Notebook to ensure transparency and reproducibility.

## Technologies Used
- **Python**: Core programming language for data analysis.
- **Pandas**: Data manipulation and analysis.
- **Matplotlib & Seaborn**: Data visualization.
- **NumPy**: Numerical computations.
- **Statsmodels**: Statistical modeling and analysis.



## Getting Started

### Prerequisites
- Python 3.8 or later
- Jupyter Notebook
- Required Python libraries (install using the command below):

```bash
pip install pandas numpy matplotlib seaborn statsmodels
```

### Running the Notebook
1. Clone the repository:
   ```bash
   git clone https://github.com/elijahcharles18/inflation-impact-analysis.git
   cd inflation-impact-analysis
   ```
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open the `Inflation Impact Analysis with Python.ipynb` file and run the cells sequentially.

## Data
The data used in this analysis is sourced from Macrotrends.net, statista.com and World Bank. Ensure the dataset is placed in the `data/` directory before running the notebook.

## Findings
The notebook outputs:
#### Trends of Exchange Rate and Inflation Rates:
![Trends of Exchange Rate and Inflation Rates](https://github.com/elijahcharles18/Inflation-Impact-Analysis-with-Python/blob/main/newplot.png)

*Figure 1: Trends of Exchange Rate and Inflation Rates*
The Naira-to-Dollar exchange rate (NGR/USD) exhibits a consistent upward trend, peaking post-2020. Nigeria’s inflation rate fluctuates but shows a rising trajectory, particularly after 2020. In contrast, the US inflation rate remains low with minor variations.

#### Correlation Analysis:


| Indicator                     | Exchange Rate (NGR/USD) | Inflation Rate (Nigeria) | Inflation Rate (United States) |
|-------------------------------|--------------------------|---------------------------|---------------------------------|
| **Exchange Rate (NGR/USD)**   | 1.000000                | 0.820133                 | 0.230760                       |
| **Inflation Rate (Nigeria)**  | 0.820133                | 1.000000                 | 0.320746                       |
| **Inflation Rate (United States)** | 0.230760            | 0.320746                 | 1.000000                       |

A correlation matrix reveals relationships among the exchange rate, Nigeria’s inflation, and US inflation. Key findings include:

Exchange Rate (NGR/USD):

Strong positive correlation with Nigeria’s inflation (0.820), indicating that a weaker Naira drives higher import costs and inflation.
Weak positive correlation with US inflation (0.231), suggesting minimal direct influence.
Nigeria’s Inflation Rate:

Strongly correlated with the exchange rate (0.820), emphasizing its sensitivity to currency depreciation.
Moderately correlated with US inflation (0.321), reflecting global economic linkages.
US Inflation Rate:

Weakly correlated with the exchange rate (0.231) and moderately with Nigeria’s inflation (0.321), indicating limited but present global economic impacts.
Key Insights:
Nigeria’s inflation is strongly influenced by exchange rate fluctuations.
Moderate correlation between US and Nigeria’s inflation highlights global interconnectedness.
Minimal impact of US inflation on the Naira/USD exchange rate.

#### Comparative Analysis: Exchange Rate vs. Inflation Rates (Nigeria & US):
![Comparative Analysis: Exchange Rate vs. Inflation Rates (Nigeria & US)](https://github.com/elijahcharles18/Inflation-Impact-Analysis-with-Python/blob/main/newplot%20(1).png).

*Figure 2: Comparative Analysis: Exchange Rate vs. Inflation Rates (Nigeria & US)*
The Nigerian inflation rate maintains a steady upward trend, while the US inflation rate remains relatively stable and low.
The exchange rate correlates more with Nigeria’s inflation rate, highlighting the influence of local economic factors on currency valuation.

#### Analyzing Inflation based on the Purchasing Power Parity (PPP)
![Analyzing Inflation based on the Purchasing Power Parity (PPP)](https://github.com/elijahcharles18/Inflation-Impact-Analysis-with-Python/blob/main/newplot(2).png)

*Figure 3: Analyzing Inflation based on the Purchasing Power Parity (PPP)*
Nigeria’s inflation rises steadily, while US inflation remains stable. The exchange rate aligns more closely with Nigeria’s inflation, underscoring local economic drivers. Purchasing Power Parity (PPP) suggests that currencies adjust over time to equalize purchasing power. However, the actual exchange rate diverges significantly from the expected PPP rate, showing a sharper rise post-2015.

## Conclusion
The graphs highlight the dynamic relationship between exchange rates and inflation rates in Nigeria and the US. Nigeria’s inflationary pressures contribute significantly to the depreciation of the Naira against the US Dollar. The divergence between the actual and expected exchange rates (PPP) suggests structural inefficiencies in Nigeria’s economy, such as trade imbalances and policy constraints. The stable US inflation rate underscores its economic resilience and monetary policy effectiveness. To address these challenges, Nigeria should focus on controlling inflation through fiscal discipline, boosting local production, and stabilizing monetary policies to improve currency valuation and economic stability.



## Contribution
Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or fixes.


## Author
**Elijah Charles Enyi**  
Economist | Data Scientist | Artificial Intelligence Enthusiast

