# Video Game Sales Analysis

This notebook contains an analytical overview of video game sales data, leveraging datasets from Kaggle and visualizations created with Tableau.

## Table of Contents

1. [Introduction](#introduction)
2. [Data Sources](#data-sources)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Project Structure](#project-structure)
6. [Results](#results)
7. [Contributing](#contributing)
8. [License](#license)
9. [Contact](#contact)

## Introduction

This project aims to analyze video game sales data to uncover trends and insights in the gaming industry. The analysis covers various aspects such as global sales, regional sales, and sales by platform, genre, and publisher. The project uses a dataset from Kaggle and presents the findings through interactive visualizations created in Tableau.

## Data Sources

- **Kaggle Video Game Sales Dataset**: The primary dataset used for analysis, which includes data on video game sales, platforms, genres, and publishers.
  - [Kaggle Dataset](https://www.kaggle.com/datasets/gregorut/videogamesales/data)
- **Tableau Dashboard**: An interactive dashboard to explore the video game sales data visually.
  - [Tableau Dashboard](https://public.tableau.com/views/VideoGameSalesAnAnalyticalOverview/Dashboard1?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Installation

To run the analysis locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/videogame-sales-analysis.git
    cd videogame-sales-analysis
    ```

2. **Create a virtual environment and activate it**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Download the dataset** from [Kaggle](https://www.kaggle.com/datasets/gregorut/videogamesales/data) and place it in the `data/` directory.

2. **Run the analysis scripts** to generate insights:
    ```bash
    python scripts/analysis_script.py
    ```

3. **Explore the results** through the Tableau dashboard available [here](https://public.tableau.com/views/VideoGameSalesAnAnalyticalOverview/Dashboard1?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).

## Results

The analysis provides insights into the following aspects of video game sales:

- **Global Sales Trends**: Overall sales trends over the years.
- **Regional Sales Analysis**: Sales distribution across different regions (NA, EU, JP, etc.).
- **Platform Analysis**: Sales performance across different gaming platforms.
- **Genre Analysis**: Popularity and sales trends across various game genres.
- **Publisher Analysis**: Sales performance of different game publishers.

The interactive Tableau dashboard allows users to explore these insights visually and gain a deeper understanding of the video game market dynamics.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or improvements, feel free to open an issue or submit a pull request.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -am 'Add a new feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
