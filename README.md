# Airbnb Price Data Analysis

This repository contains Python code for analyzing Airbnb price data. The dataset used in this analysis includes information about Airbnb listings, such as room types, prices, location, and satisfaction ratings.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Analysis Tasks](#analysis-tasks)
- [Insights and Observations](#insights-and-observations)
- [Visualization](#visualization)
- [Requirements](#requirements)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Airbnb has become a popular platform for booking accommodations worldwide. Understanding the factors that influence Airbnb prices is essential for hosts and guests alike. This repository provides Python code for analyzing Airbnb price data and extracting valuable insights.

## Dataset

The dataset used in this analysis contains information about Airbnb listings, including the following attributes:
- ID
- Room ID
- Host ID
- Room Type
- Address (City, State, Country)
- Reviews
- Overall Satisfaction
- Accommodates
- Bedrooms
- Bathrooms
- Price
- Last Modified
- Latitude
- Longitude
- Location
- Name

## Analysis Tasks

The analysis tasks performed on the Airbnb price data include:
1. Reading the data
2. Reviewing the data
3. Adding headings to columns
4. Handling missing values
5. Preliminary data analysis:
   - Calculating average price
   - Enumerating room types
   - Computing prices for different room types
   - Filtering reviews with ratings greater than or equal to 4.0
   - Segmenting and saving city names
   - Calculating average rental price per city
   - Analyzing satisfaction per city
6. Visualization:
   - Generating visualizations for various insights obtained from the data analysis

## Insights and Observations

The analysis provides insights and observations on various aspects of Airbnb pricing, including average prices, room types, reviews, satisfaction ratings, and city-wise pricing trends.

## Visualization

The visualization section includes plots and graphs illustrating trends and patterns observed during the data analysis. These visualizations help in understanding the relationships between different variables and their impact on Airbnb prices.

## Requirements

To run the code in this repository, you need the following Python libraries:
- pandas
- numpy
- matplotlib
- geopandas
- seaborn
- Pillow

You can install these libraries using the provided `requirements.txt` file.

## Usage

To use the code in this repository, follow these steps:
1. Clone the repository to your local machine.
2. Install the required Python libraries using the provided `requirements.txt` file.
3. Run the Python scripts or notebooks to perform data analysis and visualization.

## Contributing

Contributions to this repository are welcome. If you have any suggestions, enhancements, or bug fixes, please feel free to open an issue or create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
