# Cashflow-Analysis

An Investment and Cashflow Analysis made as a part of a Project done at Institue of Actuarial And Quantitative Sciences. The problem statement included an indepth Receipts and Expenditure record for an artifical Company.
Task was to evaluate the investment's profitability in the long run and another run based on our intuitions of the expected life left for the investment.
---
Discounting Rates were taken from all 3 possible assumptions:

  Arrears
```math
a_{\overline{n}} = \frac{1 - (1+i)^{-n}}{i}
```

  Advance
```math
\ddot{a}_{\overline{n}|i} = \frac{1 - (1+i)^{-n}}{d}
```

  Continuous
```math
\bar{a}_{\overline{n}|i} = \frac{1 - (1+i)^{-n}}{\delta}
```
---
A Calculation of the Internal Rate of Return (IRR) was chosen to get an idea of the investment's profitability:
```math
\sum_{t=0}^{T} \frac{CI_t}{(1 + IRR)^t} = \sum_{t=0}^{T} \frac{CO_t}{(1 + IRR)^t}
```

which is basically the rate at which the Present Value of the Cash inflows and outflows are equal.
The Project fleshed out the cashflow statements of a business, with realistic changes to costs, revenue and rates to keep it interesting.
