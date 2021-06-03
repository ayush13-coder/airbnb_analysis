# Airbnb Bookings Analysis - Team Capstone Project
## Problem Statemet:
Do exploratory data analysis(EDA) and explore and analyze the data to discover key understandings
## Inspiraton:
What can we learn about different hosts and areas?
What can we learn from predictions? (ex: locations, prices, reviews, etc)
Which hosts are the busiest and why?
Is there any noticeable difference of traffic among different areas and what could be the reason for it?

## DataSet:
**Name: Airbnb Booking Analysis**
**48895 Observations**
**16 Variables**
id: This variable contains unique id for a unique listing.
name: This gives us a small introduction about a listing. For example: Cozy Clean Guest Room - Family Apt, Large Furnished Room Near B'way etc.
host_id: This variable contains id for a host who is the host of corresponding listing.
host_name: This gives us name of the host of corresponding listing in the same row. A host_id and a host_name can come multiple times in their columns as their may be multiple listings for a single host.
neighbourhood_group: New York City is composed of five boroughs: The Bronx, Brooklyn, Manhattan, Queens, and Staten Island. These boroughs are named here as neighbourhood_group.
neighbourhood: These are the areas in their corresponding neighbourhood_group.
latitude: Latitude of the listing.
longitude: longitude of the listing.
room_type: This variable tells us about the type of listings. There are three types of listings: 'Private room', 'Entire home/apt', 'Shared room'.
price: This is the price in dollars for one night stay.
minimum_nights: minimum nights, someone can book that listing for.
number_of_reviews: Total number of reviews for that listing.
last_review: This shows date of the latest review.
reviews_per_month: number of reviews per month for that listing.
calculated_host_listings_count: amount of listings listed per host
availability_365: number of days when listing is available for booking out of 365 days.
## Steps:
**Understanding Variables:** got to know about different features available in Dataset and some stats seen at first instance.
**Univariate, Bivariate, and multivariate analysis:** explored the individual features and multiple features. Tried to get some insights.
**Data Cleaning and Outlier treatment:** cleaned the data, filled NA values, removed some outliers, and replaced the values.
**Creating new features and further analysis:** Created some new features for deep analysis and to create better models.
**Correlation Heatmap**
**Conclusion**

## Libraries used:
pandas, numpy, matplotlib, seaborn, warnings, urllib

## Plots:
Boxplots, Scatterplots, Barcharts, Piecharts, Histograms, Density Distribution
