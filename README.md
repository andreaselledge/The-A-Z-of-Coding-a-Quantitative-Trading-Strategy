# The A-Z of Coding a Quantitative Trading Strategy: A Python Series
[![Medium](https://img.shields.io/badge/Medium-Article-blue)](https://medium.com/@andreas26/the-a-z-of-creating-a-quantitative-trading-strategy-a-python-series-d0f00df0d62)

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Setup](#setup)
- [Features](#features)
- [Usage](#usage)
- [Resources](#resources)
- [Disclaimer](#disclaimer)
- [Acknowledgements](#acknowledgements)

## Introduction

👨‍💻 Author and Owner: [Andreas Elledge](https://www.linkedin.com/in/andreas-elledge-306813135/)

Creating a personal quantitative strategy is becoming increasingly popular among at-home traders and Python enthusiasts.
This project aims to walk you through the complete lifecycle of a trading strategy, starting from procuring market data to assessing the efficacy of the strategy.
The code uses $ETH prices in USD from Kraken’s API and focuses on strategies based on the Moving Average Convergence/Divergence (MACD) and the Awesome Oscillator (AO).

I'm the author and owner of this work, and it's also featured in a Medium article that you can read [here](https://medium.com/@andreas26/the-a-z-of-creating-a-quantitative-trading-strategy-a-python-series-d0f00df0d62).

## Prerequisites

- Python 3.x
- Libraries: ccxt, pandas, matplotlib, numpy, ta, quantstats
- Basic understanding of trading strategies and indicators

## Setup

1. Clone this repository.
2. Install the required packages.

    ```bash
    pip install -r requirements.txt
    ```

3. Run the notebook or script.

## Features

- Fetch historical data from Kraken using ccxt.
- Calculate MACD and AO indicators.
- Generate buy/sell signals based on strategies.
- Backtesting with quantstats.

## Usage

Open the Jupyter Notebook and run the cells sequentially to understand the process of:
- Fetching data
- Calculating indicators
- Generating trading signals
- Backtesting

## Resources

- [MACD Indicator Explained, with Formula, Examples, and Limitations](https://www.investopedia.com/)
- [A trader’s guide to using the awesome oscillator](https://www.ig.com/)
- [QuantStats Documentation](https://github.com/ranaroussi/quantstats)
- [Ta Library Documentation](https://github.com/bukosabino/ta)

## Disclaimer

The strategies implemented here are simplified versions designed for demonstrative purposes.
This project aims at enhancing Python skills and is not financial advice.

## Acknowledgements

Special thanks to Investopedia, IG International, and the open-source community for their invaluable resources.
