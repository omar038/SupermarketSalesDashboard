# Supermarket Sales Dashboard 📊

## Overview 🚀

Welcome to the **Supermarket Sales Dashboard**! This interactive Power BI project provides a comprehensive view of supermarket operations, sales performance, and customer insights. The dashboard is designed to help decision-makers quickly identify trends and derive actionable insights. Check out the overview below:

![Overview](https://github.com/omar038/SupermarketSalesDashboard/blob/main/overview/Supermarket_Sales_Dashboard.gif)

## Features ✨

- **Interactive Visuals**: Explore detailed charts, matrices, and KPIs that provide a snapshot of sales performance.
- **Blank Value Checks**: Built-in mechanisms (with DAX and Power Query) to detect and address blank values in key columns.
- **Drill-Down Analysis**: Analyze data by branch, date, product category, and more.
- **Dynamic Filtering**: Effortlessly segment your data with interactive filters.
- **Robust Data Model**: Utilizes Power Query for data cleansing and DAX for advanced calculations.

## Data Source 📦

The data used for this dashboard is sourced from [Kaggle's Supermarket Sales Dataset](https://www.kaggle.com/datasets/markmedhat/supermarket-sales/data).  
Make sure to download the dataset from Kaggle and place it in a location accessible by Power BI.

## Technologies Used 🛠

- **Power BI Desktop**: For building the dashboard and interactive visualizations.
- **DAX (Data Analysis Expressions)**: For creating dynamic measures and calculated columns.
- **Power Query**: For data extraction, transformation, and loading (ETL).
- **GitHub**: For version control and collaborative development.

## Installation and Setup ⚙️

### Prerequisites

- [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
- A Kaggle account to download the dataset
- Git (optional, for source control)

### Getting Started

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/<YourUserName>/supermarket-sales-dashboard.git
    ```

2. **Download the Data:**

   - Visit the [Kaggle Supermarket Sales Dataset](https://www.kaggle.com/datasets/markmedhat/supermarket-sales/data) page.
   - Download and extract the dataset to a known folder.

3. **Open the Project:**

   - Launch Power BI Desktop.
   - Open the provided `.pbix` file from the repository.

4. **Connect the Data Source:**

   - In Power BI Desktop, go to **Transform Data**.
   - Update the file path or connection settings so that Power BI points to your downloaded dataset.
   - Ensure the table name (e.g., `supermarket_sales`) matches the name used in the data model.

5. **Refresh Your Data:**

   - Once connected, click **Refresh** on the Home ribbon to update the visuals with the latest data.

## Usage 📈

- **Interacting with the Dashboard:**  
  Use the filters on the right pane to segment data by branch, date, or product category.
- **Data Quality Control:**  
  The dashboard includes measures and columns to flag rows with missing or blank data, allowing you to quickly assess data quality.
- **Detailed Exploration:**  
  Click on visual elements to drill down for more detailed insights into supermarket performance and trends.

## Contributing 🤝

Contributions are welcome! To contribute:

1. **Fork the Repository:**  
   Click the **Fork** button on GitHub to create your own copy.

2. **Create a Feature Branch:**

    ```bash
    git checkout -b feature/my-enhancement
    ```
    
3. **Commit Your Changes:**

    ```bash
    git commit -am "Added a new feature or fixed an issue"
    ```
    
4. **Push and Open a Pull Request:**

    ```bash
    git push origin feature/my-enhancement
    ```

Please follow the project's coding conventions and update documentation as needed.

## Issues 🐞

If you encounter any issues or have suggestions for improvements, please open an issue in this repository.

## License 📜

This project is licensed under the [MIT License](LICENSE).
