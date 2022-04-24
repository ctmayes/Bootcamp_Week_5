# Bootcamp_Week_5


# Financial Planning with APIs and Simulations

This program is designed to accomplish two tasks for members of our credit union:

Part 1: A financial planner for emergencies. The members will be able to use this tool to visualize their current savings. The members can then determine if they have enough reserves for an emergency fund.

Part 2: A financial planner for retirement. This tool will forecast the performance of their retirement portfolio in multiple time windows and portfolio weights. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

For additional reference, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

---

## Technologies

Within this program, we will make use of the following external python modules:
  -- pandas
  -- matplotlib
  -- json
  -- requests
  -- os_sys
  -- dotenv
  -- alpaca_trade_api
  -- MCForecastTools
  
  Additionally, this program was created within a python v3.7 build, and its relevant dependencies.

---

## Installation Guide

To utilize this program, within your terminal you will have to install the required libraries. Within your terminal, input the following commands:

```python
pip install pandas
```

```python
pip install matplotlib
```

```python
pip install json
```

```python
pip install requests
```
```python
pip install os_sys
```

```python
pip install python-dotenv
```

```python
pip install alpaca-trade-api
```


At the beginning of the *financial_planning_tools* file, the technologies are calling in with this code:

```
import os
import requests
import json
import pandas as pd
from dotenv import load_dotenv
import alpaca_trade_api as tradeapi
from MCForecastTools import MCSimulation

%matplotlib inline
```

---

## Usage

To operate this program, open up your terminal of choice and navigate to the directory in which you have downloaded the files within this repository. Open Jupyter Lab with the command: 

```python
jupyter lab
```  

This should open jupyter lab to the filepath in which you have the repo file, and you simply need double click the *financial_planning_tools* file to open it. Upon opening, select the menu button with two right facing arrows at the top of the notebook, which will run the entire file. It will ask you to confirm you wish to restart the file, to which you will confirm. Wait a few moments for the program to operate as intended, and peruse the resulting data at your leisure. If you wish, simply skip to the end for my analysis of the preceding information. 

---

## Contributors

Colton Mayes ctmayes@gmail.com

---

## License

This code is created for educational purposes, and it usage therein has no commerical application. It is designated as free-use thusly, and shall remain as such.
