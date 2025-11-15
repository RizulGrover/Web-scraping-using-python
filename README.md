# Stock and Revenue Data Analysis: Tesla (TSLA) & GameStop (GME)

## Overview

This project compares historical share prices with quarterly revenues for Tesla and GameStop to identify correlations and market dynamics. It demonstrates the complete workflow of collecting data from multiple sources (API and web scraping), cleaning it, and visualizing the results with interactive charts.

The analysis uses `yfinance` to fetch stock price history from the Yahoo Finance API and `BeautifulSoup` to scrape quarterly revenue data from financial websites. The results are visualized using `plotly` interactive dual-axis charts.

## Features

- Fetch historical stock data via yfinance API
- Scrape quarterly revenue data using BeautifulSoup
- Clean and transform data (remove currency symbols, handle nulls)
- Generate interactive dual-axis visualizations
- Compare fundamental performance with market price dynamics

## Getting Started

### Requirements

- Python 3.x
- pip

### Installation

Install the required libraries:

```bash
pip install yfinance pandas requests beautifulsoup4 plotly
```

Optional packages for enhanced Plotly functionality:
```bash
pip install kaleido nbformat
```

### Running the Project

1. Open the notebook:
   ```bash
   jupyter notebook "Web scraping - yfinance.ipynb"
   ```

2. Run all cells (Uncomment some parts where needed) to fetch data, clean it, and generate visualizations

3. View the generated HTML charts in the `iframe_figures/` directory

## Key Insights

**Tesla (TSLA)**: Shows a strong correlation between revenue growth and stock price appreciation. Market valuation appears justified by fundamental performance.

**GameStop (GME)**: Demonstrates a clear disconnect between fundamentals and market price. Major price spikes occurred without corresponding revenue increases, reflecting speculative trading dynamics rather than fundamental value.

## License

This project is open source and available for educational purposes.

## Author

RizulGrover

## Contributing

Contributions are welcome! Feel free to fork this repository and submit pull requests with improvements.
