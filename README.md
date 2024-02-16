# Animated Visualization of Global Health Statistics

This project aims to replicate the animated graph showcased in Hans Rosling's TED talk titled "The best stats you've ever seen". The visualization depicts the changes in life expectancy, fertility rate, and population across different countries and regions from 1960 to 2016. 

## Requirements
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Instructions
1. **Clone the Repository**: 
   ```
   git clone https://github.com/your_username/global-health-stats.git
   ```
2. **Install Dependencies**: 
   ```
   pip install pandas numpy matplotlib seaborn
   ```
3. **Run the Code**: 
   Execute the Python script `week4(saivarmapaloji).ipynb` to generate the animated graph.

## Files
- `animated_visualization.py`: Main Python script to create the animated visualization.
- `datasets/`: Directory containing the datasets used for visualization.
  - `life_expectancy.csv`: Life expectancy data.
  - `fertility_rate.csv`: Fertility rate data.
  - `population.csv`: Population data.
  - `metadata_country.csv`: Metadata containing country codes and regions.
- `README.md`: Instructions and overview of the project.

## Data Preprocessing
1. **Load Data**: Load the life expectancy, fertility rate, population, and metadata datasets.
2. **Handle Missing Values**: Handle any missing values in the datasets.
3. **Merge DataFrames**: Merge datasets as required for visualization.
4. **Data Types**: Ensure appropriate data types for analysis.

## Basic Visualizations
- **Population Trends**: Line graph showing the population trends over the years.
- **Fertility Rate Distribution**: Histogram showing the distribution of fertility rates.
- **Life Expectancy Variation**: Line graph illustrating the variation in life expectancy over the years.
- **Regional Analysis**: Analyze the health statistics based on regions.

## Animated Graph
The animated graph demonstrates the changes in life expectancy, fertility rate, and population over time. Each data point represents a country, and the color mapping distinguishes between regions. The animation provides insights into the global health trends from 1960 to 2016.

## Acknowledgments
- This project is inspired by Hans Rosling's TED talk "The best stats you've ever seen".
- Datasets are sourced from the World Bank.
- Special thanks to the Mentor [Rushikesh Konapure] for support through out this project.

## License
This dataset is provided under the [MIT License](LICENSE), allowing for unrestricted use, modification, and distribution.



## Author
SAI VARMA PALOJI
