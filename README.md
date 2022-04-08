
# Project Title: Are meme-stocks actually risky or are they worth investing in?


---

## Technologies:

The project uses python 3.7 with the following packages:

* [pandas](https://pandas.pydata.org/) - For providing data analysis and manipulation tool built on top of the Python programming language

* [requests](https://docs.python-requests.org/en/latest/) - For sending HTTP/1.1 requests

* [os](https://docs.python.org/3/library/os.html) - os module provides a portable way of using operating system dependent functionality

* [json](https://docs.python.org/3/library/json.html) - lightweight data interchange format inspired by JavaScript object literal syntax

* [load_dotenv](https://pypi.org/project/python-dotenv/) - reads key-value pairs from a .env file and can set them as environment variables

* [alpaca_trade_api](https://pypi.org/project/alpaca-trade-api/0.29/) - python library for the Alpaca trade API. It allows rapid trading algo development easily, with support for the both REST and streaming interfaces

* [MCSimulation](https://www.rdocumentation.org/packages/decisionSupport/versions/1.110/topics/mcSimulation) - generates a random sample of an output distribution defined as the transformation of an input distribution by a mathematical model

* [%matplotlib inline](https://pythonguides.com/what-is-matplotlib-inline/) -  enable the inline plotting, where the plots/graphs will be displayed just below the cell where your plotting commands are written

---

## Installation Guide


Before running the application first install the following dependencies:

```python
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

To run the financial tool program, simply clone the repository,  establish API keys for alpaca, and go through the written steps in the *.ipynb file.

---

## Contributors

Sungmoo Ban
Ryan Johnson
Jung Kim
Jennifer Taylor
Danica Valera


---

## License

MIT License
