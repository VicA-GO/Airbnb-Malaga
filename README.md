### README

# Analysis of the Airbnb Market in Málaga

## Introduction

This project presents an analysis of the vacation rental market of Airbnb in Málaga. Using a detailed dataset from Airbnb, we have explored the geographical distribution, historical growth, and key characteristics of listings in the city. Our goal is to provide valuable insights that can be used by tourism companies and vacation rental platforms to enhance user experience and optimize their operations.

## Data Source

This is an external data source provided by #Inside Airbnb Network (https://insideairbnb.com/get-the-data/), an activist project with the mission of offering data that quantifies the impact of short-term rentals on housing and residential communities. Inside Airbnb Network claims not to be associated with or endorsed by Airbnb or any of its competitors.

## Data Content

The data consists of 8 different datasets:
- **listings.csv**: Detailed Listings data. Contains all the advertisements in Málaga on June 30th, 2024. 8976 rows and 75 variables.
- **calendar.csv**: Detailed Calendar Data. The calendar has 365 records for each listing. It specifies whether the listing is available on a particular day (365 days ahead) and the price on that day.
- **reviews.csv**: Detailed Review Data. Contains comments of listings, dates, and reviewers.
- **listings SUMMARY.csv**: Summary information and metrics for listings in Málaga. 18 variables.
- **reviews SUMMARY.csv**: Listing ID and date of the review.
- **neighbourhood.csv**: Neighbourhood list for geo filter.
- **neighbourhoods.geojson**: GeoJSON file of the neighbourhoods of the city.
- **Inside Airbnb Data Dictionary - listings.csv detail v4.3.pdf**: Data dictionary contains data type and description of listings.csv.

## Analysis and Results

## Scripts

The scripts in the SCRIPT folder of the repository correspond to the different exercises performed during the analysis:

1. **6.1. Sourcing Open Data**
2. **6.2. Exploring Relationships**
3. **6.3. Geographical Visualizations with Python**
4. **6.4. Supervised Machine Learning: Regression**
5. **6.5. Unsupervised Machine Learning: Clustering**
6. **6.6. Sourcing & Analyzing Time Series Data**

## Storyboard on Tableau

For a summarized view of the analysis results, visit my [Tableau Storyboard](https://public.tableau.com/shared/DZWRTFNR6?:display_count=n&:origin=viz_share_link).

## Conclusion

This project demonstrates how data analysis can provide valuable insights into the Airbnb vacation rental market in Málaga. Although the presented interactive dashboard is just a sample, there are many additional features that can be incorporated into future analyses to gain a more comprehensive view of the market.
