# Understat Scraper

## Overview
The Understat Scraper is a Python project designed to extract football match data from the Understat website. It utilizes web scraping techniques to gather data on match statistics, including expected goals (xG), shot locations, and results. The project is structured to provide both a script for automated scraping and a Jupyter notebook for interactive data exploration.

## Project Structure
```
understat-scraper
├── src
│   └── scraper.py          # Main scraping logic
├── notebooks
│   └── understat_scraper.ipynb  # Interactive Jupyter notebook for scraping
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
```

## Installation
To set up the project, follow these steps:

1. Clone the repository:
   ```
   git clone <repository-url>
   cd understat-scraper
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage
### Running the Scraper
You can run the scraper by executing the `scraper.py` script located in the `src` directory. This script contains the main logic for scraping data from the Understat website.

### Using the Jupyter Notebook
The `understat_scraper.ipynb` notebook provides an interactive environment to run the scraping code. You can open it using Jupyter Notebook or Jupyter Lab:

1. Start Jupyter Notebook:
   ```
   jupyter notebook
   ```

2. Open `notebooks/understat_scraper.ipynb` and follow the instructions within the notebook to scrape data and analyze results.

## Requirements
The project requires the following Python libraries:
- requests
- beautifulsoup4
- pandas

These libraries are listed in the `requirements.txt` file.

## Contributing
Contributions are welcome! If you have suggestions for improvements or new features, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
