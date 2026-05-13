# Data Analysis - Python Projects

This project contains two comprehensive data analyses performed in Python using Jupyter Notebook. Each analysis explores real-world datasets to answer specific business questions.

## Project Structure

```
Data_Analyse_Python_Project/
├── projet1_analyse_COVID19.ipynb
├── Projet2_Analyse_Ventes_Supermarchés.ipynb
├── COVID-19-geographic-distribution-worldwide-2020-12-14-_2_.csv
├── all_data(ventes_super_marché).csv
└── README.md
```

## Project 1: COVID-19 Data Analysis (2020)

### Description
Exploratory analysis of geographic distribution data for COVID-19 worldwide during 2020.

### Objectives
- Identify countries with the highest number of confirmed cases
- Evaluate mortality rates by country and region
- Compare COVID-19 situation across continents
- Analyze the evolution of deaths and cases throughout the year
- Establish potential relationship between country population and case numbers

### Data
- **File**: `COVID-19-geographic-distribution-worldwide-2020-12-14-_2_.csv`
- **Dimensions**: 61,900 rows x 12 columns
- **Coverage**: 214 countries and 6 continents
- **Key Variables**: country, continent, confirmed cases, deaths, population

### Methods Used
- Data cleaning and missing value handling
- Descriptive statistical analysis
- Comparative visualizations by country and continent
- Correlation and bivariate analyses

## Project 2: Supermarket Sales Analysis

### Description
Analysis of supermarket sales data to optimize commercial strategies and understand customer purchasing behavior.

### Objectives
- Identify the best performing month in terms of revenue
- Determine optimal hours for advertising campaigns
- Analyze sales by geographic location
- Identify products frequently purchased together
- Rank products by popularity

### Data
- **File**: `all_data(ventes_super_marché).csv`
- **Key Variables**: order ID, products, quantity, price, date, time, delivery address

### Methods Used
- Data processing and validation
- Temporal analysis (by month, by hour)
- Geographic sales analysis
- Product association analysis
- Commercial visualizations

## Requirements

Ensure you have installed the following dependencies:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

## Technologies Used

- **Python 3.x**
- **Jupyter Notebook**: For exploratory analysis and documentation
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computations
- **Matplotlib & Seaborn**: Data visualizations

## Usage

1. Clone or download the project
2. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Navigate to the project folder
4. Open the desired notebooks:
   - `projet1_analyse_COVID19.ipynb`
   - `Projet2_Analyse_Ventes_Supermarchés.ipynb`
5. Execute cells to generate analyses and visualizations

## Expected Results

Each notebook produces:
- Detailed descriptive statistics
- Graphical visualizations (histograms, pie charts, correlations)
- Conclusions and recommendations
- Actionable business insights

## Author

TCHOUANANG GHEMDJOK PASCAL DIMITRI

## License

This project is provided for educational purposes.
