# Efficient Frontier Portfolio Management

This project implements modern portfolio theory using the efficient frontier approach to optimize investment portfolios. It provides tools for data processing, portfolio optimization, and risk analysis.

## Project Structure

The project consists of three main Jupyter notebooks:

- `src/dataprocessing.ipynb`: Handles data collection, cleaning, and preprocessing of financial data
- `src/efmodelling.ipynb`: Implements the efficient frontier model and portfolio optimization
- `src/Risk_free_asset.ipynb`: Extends the efficient frontier model to include risk-free assets

## Features

- Data processing and cleaning of financial time series
- Calculation of expected returns and covariance matrices
- Efficient frontier optimization
- Portfolio risk analysis
- Visualization of optimal portfolios
- Integration of risk-free assets

## Dependencies

The project requires the following Python packages:
- pandas
- numpy
- matplotlib
- python-dateutil
- pytz

## Usage

1. Start with `dataprocessing.ipynb` to prepare your financial data
2. Use `efmodelling.ipynb` to optimize your portfolio using the efficient frontier
3. Optionally use `Risk_free_asset.ipynb` to include risk-free assets in your analysis

## Getting Started

1. Clone the repository
2. Install the required dependencies:
   ```bash
   pip install pandas numpy matplotlib
   ```
3. Open the Jupyter notebooks in your preferred environment
4. Follow the notebooks in sequence to process data and optimize your portfolio

## License

This project is open source and available under the MIT License.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
