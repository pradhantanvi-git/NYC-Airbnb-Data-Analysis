# Airbnb NYC 2019 – Data Analysis

## Project Overview
This project explores short-term rental properties in New York City using the **AIRBNB_NYC_2019** dataset, which consists of nearly 49,000 listings. The goal is to analyze pricing strategies, occupancy rates, and the influence of reviews on rental attractiveness. The insights gained from this analysis can help **hosts, policymakers, and potential renters** make informed decisions.

## Research Questions
The analysis aims to address the following key questions:
1. **How does the average price vary across different neighborhoods and room types?**
2. **How do reviews and their frequency influence a listing’s price and occupancy rates?**
3. **What are the patterns in the spatial distribution of Airbnb listings across NYC’s neighborhoods?**
4. **What is the distribution and popularity of different room types?**
5. **How do minimum nights and listing availability correlate with pricing strategies?**

## Dataset
The **AIRBNB_NYC_2019** dataset includes key variables such as:
- Listing ID
- Host ID
- Neighborhood group & neighborhood
- Room type
- Price
- Minimum nights
- Number of reviews
- Last review date
- Reviews per month
- Availability over 365 days

### Data Preprocessing
- **Data Cleaning**: Handled missing values, removed outliers, and corrected inconsistencies.
- **Data Transformation**: Applied one-hot encoding, converted date columns, and normalized the price variable.

## Methodology
The project follows these steps:
1. **Data Collection & Cleaning**: Preparing the dataset for analysis.
2. **Exploratory Data Analysis (EDA)**: Understanding patterns and relationships.
3. **Visualization**: Using charts and maps for insights.
4. **Statistical & Machine Learning Analysis**: Identifying trends and making predictions.
5. **Conclusion & Recommendations**: Summarizing key findings.

## Tools & Technologies Used
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Jupyter Notebook**
- **Geospatial Visualization** (Folium)
- **Machine Learning** (Scikit-Learn)

## Contributors
- **Tanvi Pradhan**
- **Priya Vora**
- **Keshav Ch**

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
This project is part of the **IST 652 – Scripting for Data Analysis** course. The dataset is publicly available and sourced from [Airbnb Open Data](https://huggingface.co/datasets/gradio/NYC-Airbnb-Open-Data/tree/main).
