# Montreal Statistics' Map Dashboard

![Montreal Statistics' Map Dashboard](dashboard_screenshot.png)

This project is a web-based dashboard application that visualizes statistical data about Montreal on an interactive map. It allows users to explore various datasets, including population, household types, and income, across different geographic areas in Montreal.

## Features

- Interactive choropleth map visualization using Plotly Express.
- Select different datasets and columns to visualize on the map.
- Clean and easy-to-use interface with responsive design.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Data Sources](#data-sources)
- [License](#license)
- [Authors](#authors)

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/edin98/MTL_map_AWS.git

2. Navigate to the project directory:

   ```bash
   cd MTL_map_AWS
   
3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt

## Usage
1. Run the Dash application:

   ```bash
   python app.py
2. Open a web browser and navigate to http://127.0.0.1:8052/ to access the dashboard.

3. Explore the dashboard by selecting different datasets to visualize on the map.

## Data Sources

- Geometric data (GeoJSON format) retrieved from [Canada Statistics website](https://www.statcan.gc.ca/en/start).
- Statistical data (CSV format) retrieved from [Canada Statistics website](https://www.statcan.gc.ca/en/start).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


## Authors

- [Edinson Arita](https://github.com/edin98)


