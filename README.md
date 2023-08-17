# ETF_Analyst

# ETF Data Analysis and Visualization

This project involves the analysis and visualization of Exchange-Traded Fund (ETF) data using Python and various libraries, including Pandas, NumPy, Matplotlib, and Seaborn. The goal is to gain insights into ETF trading volume, mean prices, returns, volatility, and correlation.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Data Preparation](#data-preparation)
- [Analysis and Visualization](#analysis-and-visualization)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project provides a Python script that reads and analyzes ETF data from CSV files stored in a specified directory. The script performs various data cleaning, calculation, and visualization tasks to provide insights into ETF trading patterns and performance.

## Getting Started

To use this project, you'll need Python and the required libraries installed on your system. You can install the required libraries using the following command:

```bash
pip install pandas numpy matplotlib seaborn
```


Clone this repository to your local machine using:

<pre><div class="bg-black rounded-md mb-4"><div class="flex items-center relative text-gray-200 bg-gray-800 px-4 py-2 text-xs font-sans justify-between rounded-t-md"><span>bash</span><button class="flex ml-auto gap-2"><svg stroke="currentColor" fill="none" stroke-width="2" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round" class="h-4 w-4" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M16 4h2a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h2"></path><rect x="8" y="2" width="8" height="4" rx="1" ry="1"></rect></svg>Copy code</button></div><div class="p-4 overflow-y-auto"><code class="!whitespace-pre hljs language-bash">git clone https://github.com/yourusername/etf-analysis.git</code></div></div></pre>


## Usage

1. Place your ETF data CSV files in the 'database' directory.
2. Modify the `database_path` variable in the script to point to the location of your CSV files.
3. Run the script using a Python interpreter:

<pre><div class="bg-black rounded-md mb-4"><div class="flex items-center relative text-gray-200 bg-gray-800 px-4 py-2 text-xs font-sans justify-between rounded-t-md"><span>bash</span><button class="flex ml-auto gap-2"><svg stroke="currentColor" fill="none" stroke-width="2" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round" class="h-4 w-4" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M16 4h2a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h2"></path><rect x="8" y="2" width="8" height="4" rx="1" ry="1"></rect></svg>Copy code</button></div><div class="p-4 overflow-y-auto"><code class="!whitespace-pre hljs language-bash">python etf_analysis.py
</code></div></div></pre>

## Data Preparation

The script reads CSV files in the specified directory, combines them into a single dataframe, and performs the following data preparation steps:

* Converts 'Date' column to datetime format.
* Adds 'Year', 'Month', and 'Day' columns extracted from 'Date'.
* Calculates mean values of 'Open', 'High', 'Low', and 'Close' columns.
* Computes daily returns and annualized volatility.
* Calculates and visualizes correlation matrix of ETF returns.

## Analysis and Visualization

The script performs the following analysis and visualization tasks:

* Visualizes total trading volume for each ETF.
* Generates line plots for trading volume and mean price analysis.
* Calculates and displays percentage difference in prices.
* Plots individual return analysis for each ETF.
* Creates heatmap to visualize correlation between ETF returns.

## Contributing

Contributions are welcome! If you find any issues or want to add improvements, feel free to open a pull request or submit an issue.
