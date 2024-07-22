# Data Source: https://github.com/spribylova/PythonBank

## Data descriptions
1. Outstanding loans — Columns: RiskLevel, YOB, LGD, EAD
2. Old loans — Columns: ID, RiskLevel, YOB, Year, Default
3. Simplified Fed history (years 2000 – 2017) — Columns: Year, DJX Return, GDP
4. Simplified adverse (years 2018, 2019, 2020) — Columns: Year, DJX, GDP

### Column descriptions:
Independent variables are: 
	- RiskLevel, YOB (Years On Book), 
	- LGD (Loss Given Default), 
	- EAD (exposure at default), 
	- ID (Primary Key), Year,
	- DJX Return (Dow Jones Index),
	- GDP (Gross Domestic Product)

Dependent variable:
	- Default is the response/dependent variable, failures to fulfil a loan obligation. 
	- Higher the Default, higher the chance the loan will not be repaid.
