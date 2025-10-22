# Data Processing Project
## Summary
This project involves data processing using Python and Pandas. It takes an input Excel file, processes it using a Python script, and generates a JSON output. The project utilizes GitHub Actions for continuous integration and deployment.

## Setup
To view the results, simply open the published GitHub Pages site.

## Usage
1. Clone the repository to your local machine.
2. Install the required dependencies, including Python 3.11+ and Pandas 2.0.
3. Run the `execute.py` script to generate the `result.json` file locally.
4. View the results in the `result.json` file or on the published GitHub Pages site.

## Code Explanation
The project consists of a Python script (`execute.py`) that processes an input CSV file (`data.csv`) using Pandas. The script generates a JSON output, which is then published via GitHub Pages using a GitHub Actions workflow defined in `.github/workflows/ci.yml`. The workflow also runs `ruff` for code linting and displays its results in the CI log.

## License
This project is licensed under the MIT License.