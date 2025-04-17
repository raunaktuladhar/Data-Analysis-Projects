# 🛌 Airbnb Analysis

<br>

## 📅 Project Overview
This project analyzes Airbnb listing data to understand pricing trends, customer preferences, and location-based availability. The goal is to extract meaningful insights that can help hosts optimize their listings and guide Airbnb in enhancing the overall guest experience.

<br>

## 📚 Dataset

* __Source:__ compressed_data.csv.gz (given above) (It is a zip file containing csv file for Airbnb)
* __Columns:__
    - `id` -> ID of the hotel
    - `NAME` -> Name of the hotel
    - `host id` -> ID of the host
    - `host_identity_verified` -> Whether the identity of host is verified or not
    - `host name` -> Name of the host
    - `neighbourhood group` -> Group of neighbourhood
    - `neighbourhood` -> Name of the neighbourhood
    - `lat` -> latitude of the area
    - `long` -> longitude of the area
    - `country` -> Name of the country 
    - `country code` -> Code of the country
    - `instant_bookable` -> Whether the hotel is instantly bookable or not
    - `cancellation_policy` -> Whether the cancellation policy is strict or not
    - `room type` -> Types of room
    - `Construction year` -> Year of Construction
    - `price` -> Price of the hotel
    - `service fee` -> Price of service fee
    - `minimum nights` -> No. of nights that can be spent
    - `number of reviews` -> Reviews given by the guests
    - `last review` -> Date of recent review
    - `reviews per month` -> Reviews getting per month
    - `review rate number` -> Reviews out of 5
    - `calculated host listings count` -> No. of host listings
    - `availability 365` -> No. of availability days in a year
    - `house_rules` -> Policy of the hotel
    - `license` -> Not given for a reason

<br>

## 🛠️ Tools & Libraries Used
1. Python(Numpy, Pandas, Seaborn, Matplotlib)
2. Jupyter Notebook

<br>

## 📊 Key Questions & Insights

1. What is the distribution of listing prices?
   * The histogram shows a fairly even distribution of listing prices across different price ranges, indicating no particular concentration of listings in any specific price range. The KDE line helps to visualize this even spread more clearly, confirming that the dataset contains listings with a wide variety of prices.
   
2. How are different room types distributed?
   * Room types are distributed by the following:

     1. Private room
     2. Entire home / Apartment
     3. Shared room
     4. Hotel room

3. How are listings distributed across different neighbourhoods?
   * The listings are distributed across different neighborhoods by the following:
       1. Brooklyn
       2. Manhattan
       3. brookIn
       4. manhatan
       5. Queens
       6. Staten Island
       7. Bronx
   
4. What is the relationships between price and room type?
   * Private room costs around 400 - 900
   * Entire home / Apartment costs around same as Private room
   * Shared room costs around same as Private room and Apartment
   * Hotel room costs around 500 - 900

5. How has number of reviews changed over time?
    * The year 2019 had the highest no. of reviews
