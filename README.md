# LETF-Returns-2020

## Introduction

This is the final project in Advanced Topic in Applied Math --- Stochastic Modeling in Econ., taught by Prof. Avellaneda at NYU in 2021 Spring. 

Abstract: "Last year (2020) was an extremely tough year for the market worldwide. The Chicago Board Options Exchange’s CBOE Volatility Index (VIX), which based on S&P 500 options reached the highest point for the past five years. The average of VIX was extremely high in history. The other notable peak was in 2008 during the financial crisis which Avellaneda and Zhang’s paper was produced soon after. We can observe some similar behaviors of the leveraged ETFs, such as the under performances of the leveraged ETFs. In this study, we will use the discrete-time model in the original paper to produce the returns of 20 double-long and double-short leveraged ETFs from 2020 - 2021. Moreover, the estimation of instantaneous variance in the discrete-time model cannot be evaluated in a continuous manner. However, we can reduce the range for the evaluation of the variance to produce a more accurate output for the returns.
" 

The original discrete-time model can be found here.

https://papers.ssrn.com/sol3/papers.cfm?abstract_id=1404708.



## Structure 

Two files:

- The raw data in the form of Excel (LOL)

  This contains the ETF prices from Yahoo Finance. Tracking errors and stds are calculated under this file.  

- Results and conclusions in the .pdf file

A lot of thanks to my classmate Bill Xu, who gathered all the necessary Expanse Ratio (f) and correct my mistakes!!! 

## Open Question

In this project, we used the discrete-time model, which means that the instantaneous volatility is calculated from the variance 5-day returns. However, the accuracy of the path-dependence model can be improved by using a continuous way to calculate the instantaneous volatility. 

Some suggestions can be found here. 

[1] Oleh Danyliv and Bruce Bland. An Instantaneous Market Volatility Estima- tion. SSRN, 2019. https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3434093

Or simply by Googling "instantaneous volatility". 
