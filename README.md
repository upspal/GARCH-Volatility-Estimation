# GARCH-Volatility-Estimation

This project implements GARCH(1,1) model to estimate volatility for TCS, Infosys, Asian Paints, and Bajaj over various timeframes. The analysis was conducted using the GARCH.ipynb notebook.

## Results Summary
### Volatility Analysis by Company

#### TCS
| Period | Raw Volatility | Annualized Volatility (%) |
|--------|---------------|------------------------|
| 3M     | 1.4605       | 23.18                 |
| 6M     | 1.4993       | 23.80                 |
| 9M     | 1.4859       | 23.59                 |
| Full   | 1.4170       | 22.49                 |

#### Infosys
| Period | Raw Volatility | Annualized Volatility (%) |
|--------|---------------|------------------------|
| 3M     | 1.6506       | 26.20                 |
| 6M     | 1.5318       | 24.32                 |
| 9M     | 1.4759       | 23.43                 |
| Full   | 1.5558       | 24.70                 |

#### Bajaj
| Period | Raw Volatility | Annualized Volatility (%) |
|--------|---------------|------------------------|
| 3M     | 1.4488       | 23.00                 |
| 6M     | 1.5423       | 24.48                 |
| 9M     | 1.4769       | 23.44                 |
| Full   | 1.4782       | 23.47                 |

#### Asian Paints
| Period | Raw Volatility | Annualized Volatility (%) |
|--------|---------------|------------------------|
| 3M     | 1.4228       | 22.59                 |
| 6M     | 1.4446       | 22.93                 |
| 9M     | 1.3748       | 21.82                 |
| Full   | 1.4933       | 23.71                 |

## Key Findings

The analysis reveals several interesting patterns in volatility across different time periods:

1. **Variable Time Horizon Effects:** Contrary to initial assumptions, longer time horizons don't consistently show higher volatility. For instance, TCS shows lower volatility (22.49%) in the full period compared to shorter timeframes.

2. **Company-Specific Patterns:** 
    - Infosys displays the highest volatility among all companies in the 3M period (26.20%)
    - Asian Paints shows relatively stable volatility across different periods, with a slight increase in the full period
    - Bajaj maintains consistent volatility levels across all timeframes (around 23-24%)

3. **Short-term vs Long-term Dynamics:** The 3M volatility measurements often differ significantly from full-period estimates, suggesting distinct short-term market dynamics affecting each company differently.

## How to Run the Code

1. Clone this repository
2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```
3. Ensure the CSV files are present in the `data` folder
4. Open and run `GARCH.ipynb` using Jupyter Notebook or JupyterLab

