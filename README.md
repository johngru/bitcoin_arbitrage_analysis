# Bitcoin Arbitrage Analysis

<img src="./Resources/bitcoin_readme.jpg" alt="bitcoin" width=50% class="center"/>

A report summarized in a Jupyter notebook gathering, cleaning, analyzing, and computing previously profitable arbitrage opportunities between [Bitstamp](https://www.bitstamp.net/) and [Coinbase](https://www.coinbase.com/).  

---

## Technologies

This project is written using a ```Jupyter Lab 3.2.1``` notebook running  ```Python 3.7.11```.  Key libraries include ```pandas 1.3.5``` for importing and analyzing the data from csv files,```matplotlib 3.5.0``` for plotting the data, and the standard python package for file name management ```pathlib```.

---

## Installation Guide

Before running the application, first install the following packages if you don't already have them installed in your development environment.

```python
  pip install jupyterlab
```
After installation, ```cd``` into the top folder of the repository.  Then open ```Jupyter Lab``` by typing:
```python
jupyter lab
```
This should open an instance of Jupyter lab in your default explorer applicaiton.  The report and analysis are in the jupyter notebook file named ```crypto_arbitrage.ipynb```.  Open this file and the contents form the basis of the report.

---

## Usage

This Jupyter notebook is intended as an analysis of previous profitable arbitrage opportunities of bitcoin on [Bitstamp](https://www.bitstamp.net/) and [Coinbase](https://www.coinbase.com/).

To view the analysis, open up a gitbash or terminal in the top folder of the cloned repository.  To view the analysis, open the ```crypto_arbitrage.ipynb``` file, which should look like the displayed version below:

<img src="./Resources/bitcoin_arbitrage_start.png" alt="bitcoin_arbitrage_report_preview" width="50%"/>

Simply run the Kernel and the results/analysis will populate the report.

## Data Set Information

The data used in this report is taken from exchange data from [Bitstamp](https://www.bitstamp.net/) and [Coinbase](https://www.coinbase.com/).  These files are located in the ```Resources``` directory and are named ```bitstamp.csv``` and ```coinbase.csv```, respectively.  Each file contains the timestamp (incremented by the minute), open bitcoin price, close bitcoin price, the high, the low, the BTC Volume, the USD Volume, and the Weighted Price.  For this analysis, only the close price is considered from each exchange.  The data convers the first quarter of 2018, which is from January 1st - March 31st, 2018. 

---

## Contributors

The seed code is from the course material from a UCBerkeley Extension program.  This analysis is written and performed by John Gruenewald.<br><br>
For more information, contact **John Gruenewald**:<br>
**e-mail:** [john.h.gruenewald@gmail.com](mailto:john.h.gruenewald@gmail.com)<br> **linked-in:**  [jhgruenewald](https://www.linkedin.com/in/jhgruenewald/)<br>**twitter:**  [@GruenewaldJohn](https://twitter.com/GruenewaldJohn)<br>**medium:**  [@comput99](https://medium.com/@comput99)

---

## License

MIT License

Copyright (c) 2022 John Gruenewald
