# Analyzing Global Air Quality Index (AQI) Data

## Overview

This project analyzes the Air Quality Index (AQI) data from various cities around the world. The primary goals are to identify trends, compare air quality across different regions, and investigate the impact of certain events (like holidays, wildfires, or policy changes) on air quality. The project leverages Python's pandas for data manipulation, matplotlib and seaborn for data visualization, and sklearn for basic predictive modeling.

## Table of Contents

- [Installation](#installation)
- [Data Collection](#data-collection)
- [Data Exploration and Analysis](#data-exploration-and-analysis)
- [Visualization and Interpretation](#visualization-and-interpretation)
- [Optional Extensions](#optional-extensions)
- [Dataset](#dataset)
- [Contributers](#contributers)
- [Contributing](#contributing)
- [License](#license)

## Installation

To get started, clone the repository and install the required dependencies:

```bash
git clone [https://github.com/Campeon254/Air-Quality-Analysis]
cd Air-Quality-Analysis
pip install -r requirements.txt
```

## Data Collection

We use the OpenAQ API to collect AQI data from various cities. The dataset includes key pollutants such as PM2.5, PM10, CO, NO2,and O3. You can find the API documentation [here](https://docs.openaq.org/).

## How to Access the Data

- **OpenAQ API:** Use the API to filter data by date, location, and pollutant.
- **Downloadable Files:** OpenAQ provides periodic data dumps available for download [here](https://openaq.org/#/download).

## The file code for this project is named "Analysis (combined cities).ipynb " you can acess it from files _To run succesfully the code

go to code>>copy the URL>>open VsCode>>shift+ctrl+p>>clone>>paste the URL>>enter>>select the https://
github.com/Campeon254/Air-Quality-Analysis(The repository URL)>>Select local folder>>Make changes and commits>>Push Changes to gitHub.

## Data Exploration and Analysis

Once the data is collected, we perform the following tasks:

- **Data Cleaning:** Handle missing values, duplicate entries, and data types.
- **Data Exploration:** Calculate summary statistics and understand data distribution using histograms, box plots, and scatter plots.
- **Time-Series Analysis:** Analyze AQI trends over time for selected cities.
- **Comparative Analysis:** Compare AQI data across different cities or regions to identify areas with the best and worst air quality.

## Visualization and Interpretation

We create compelling visualizations to represent our findings using matplotlib and seaborn. These include:

- Time series plots showing AQI trends for selected cities.
- Bar charts comparing AQI across different cities.
- Heatmaps visualizing AQI by month.

We then interpret the results and discuss potential reasons behind air quality trends and differences between cities or regions.

## Optional Extensions

- **Predictive Modeling:** Use basic machine learning models from sklearn to predict future AQI levels based on historical data.
- **Impact of Events:** Analyze the impact of specific events (e.g., New Year's Eve, major wildfires, policy changes) on air quality.

## Dataset

### Key Features

- **Global Coverage:** Data from thousands of stations worldwide.
- **Pollutants Measured:** PM2.5, PM10, CO, NO2,O3 and more.
- **Open and Free:** Available for educational and research purposes.

### Access the Data

- **API Access:** Programmatic access to the data via OpenAQ API.
- **Data Dumps:** Periodic data dumps available for download from the OpenAQ website or GitHub.

## Contributers

This was a combined collaborations between my group.
The group members included:

Snit Teshome, 670552

Whitney Gituara, 671528

Selmah Tzindori, 669602

Andy Hadulo, 668059

Ogutu Rufinus, 670827

Calvin Gacheru, 670035

## Contributing

We welcome contributions! Please fork the repository and submit a pull request with your changes. Ensure that your code adheres to our coding standards and includes appropriate tests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
