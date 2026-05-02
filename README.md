# Car Analysis & Visualization

This project provides a comprehensive exploratory data analysis (EDA) and visualization of a car dataset (`cars.csv`). The analysis is performed in a Jupyter Notebook, utilizing popular Python libraries to uncover trends, distributions, and relationships between various car specifications.

## Project Overview

The goal of this project is to analyze various features of automobiles, such as price, fuel efficiency (MPG), engine size, horsepower, and more. Through visualization, we aim to understand:
- The distribution of car prices and engine sizes.
- Market share based on origin (USA vs. non-USA).
- Preferences for different car types (Small, Midsize, Compact, etc.).
- Correlations between performance metrics like Horsepower and Price.

## Dataset

The dataset `cars.csv` includes 93 entries with the following key features:
- **Manufacturer & Model**: The make and specific model of the car.
- **Type**: Category of the car (e.g., Small, Midsize, Large, Sporty).
- **Price**: The manufacturer's suggested retail price (MSRP).
- **MPG (City & Highway)**: Fuel efficiency in different driving conditions.
- **EngineSize & Horsepower**: Performance-related specifications.
- **Weight**: Total weight of the vehicle.
- **Origin**: Manufacturing region (USA or non-USA).

## Key Visualizations

The `Anlysis.ipynb` notebook includes several detailed plots:
- **Histograms**: To visualize the frequency distribution of `Price` and `EngineSize`.
- **Count Plots**: Comparing the number of vehicles based on `Origin` and `Type`.
- **Pie Charts**: Showcasing the percentage distribution of `Origin`, `Type`, and `DriveTrain`.
- **Scatter Plots**: Exploring the relationship between `Price` and `Horsepower`.
- **Box Plots**: Analyzing the price range across different car `Types`.
- **Heatmaps & Pairplots**: Identifying correlations between multiple numeric variables.

## Technologies Used

- **Python**: Core programming language.
- **Pandas**: Data manipulation and analysis.
- **Matplotlib**: Basic plotting and visualization.
- **Seaborn**: Advanced statistical data visualization.

## How to Use

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   ```
2. **Install dependencies**:
   Ensure you have Python installed, then install the required libraries:
   ```bash
   pip install pandas matplotlib seaborn notebook
   ```
3. **Run the analysis**:
   Launch Jupyter Notebook and open `Anlysis.ipynb`:
   ```bash
   jupyter notebook Anlysis.ipynb
   ```

## Conclusion

This analysis provides valuable insights into the 1993 car market, highlighting trends in pricing, performance, and regional manufacturing preferences.
