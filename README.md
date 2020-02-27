# AirBnB-listings
A Look Into Home Availability, Pricing and Reviews

### Table of Contents

1. [Project Motivation](#motivation)
2. [File Descriptions](#files)
3. [How to Interact with the project](#libraries)
4. [Licensing, Authors, and Acknowledgements](#sources)

## Motivation
We will take a closer look at the AirBnB listings associated with Lyon and Bordeaux (France). We will try to answer these questions below, in the Jupyter notebook and there (https://medium.com/@vally.selvarasa/airbnb-in-france-lyon-vs-bordeaux-616315f8d2ec). 

- How are the availability and the pricing of the properties in both cities throughout the year?
- Who visit more each of the cities ?
- How does the pricing increase or decrease by neighborhood in Lyon ?
- How well can we predict an Airbnb’s price? Which variables are important in the prediction?

## Files
* `calendar_Lyon.csv` and `calendar_Bordeaux.csv` - csv containing **availability**, and **price** for every listing/date combination

* `listings_Lyon.csv` and `listings_Bordeaux.csv` - **id**, information about **location, reviews, amenities, price...** for each listing

* `reviews_Lyon.csv` and `reviews_Bordeaux.csv` - csv containing the **listing_id**, **date** of review, **reviewer_id**, **reviewer_name**, and reviewer **comments** for the reviewed stays.

## Libraries
Python 3.7.3

The libraries we will be using will be:

[folium] (https://python-visualization.github.io/folium/)

[langdetect] (https://pypi.org/project/langdetect/)

## Sources

Data used are provided by AirBnB : [data](http://insideairbnb.com/get-the-data.html)
