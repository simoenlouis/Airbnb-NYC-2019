# Airbnb-NYC-2019

Kaggle Link:(https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data)

# Airbnb NYC 2019 Data Analysis Report

## Project Overview

This project analyzes the Airbnb NYC 2019 dataset to understand the factors that influence listing demand, pricing, and customer behavior across New York City boroughs.

The analysis focuses on identifying:

* The most demanded areas and property types
* Factors associated with higher prices
* Characteristics of highly reviewed listings
* Differences between professional hosts and smaller hosts
* The impact of listing descriptions and keywords on customer interest

---

# Data Cleaning & Preparation

Several preprocessing steps were performed before the analysis:

* Missing values in `name` and `host_name` were filled with `"No name"`
* Unnecessary columns such as IDs, coordinates, and review dates were removed
* Listings with missing prices were imputed using the median price based on:

  * `neighbourhood_group`
  * `room_type`

Additionally, extreme price values were investigated carefully instead of being removed automatically, since many high-priced listings represented real luxury properties with customer reviews and demand.

---

# Key Findings

## 1. Manhattan Has the Highest Prices

Manhattan was identified as the most expensive borough in the dataset.

Possible reasons include:

* High tourism activity
* Proximity to attractions and transportation
* Luxury and premium listings
* Larger and more private accommodations

The analysis also showed that many high-priced listings in Manhattan are entire homes or apartments, offering greater privacy and premium experiences.

---

## 2. Privacy Strongly Influences Demand and Price

Listings offering greater privacy tend to have:

* Higher prices
* Higher customer demand
* More reviews

Entire homes/apartments generally performed better than shared rooms, suggesting that customers value comfort and privacy.

---

## 3. Lower Availability May Indicate Higher Demand

Listings with lower `availability_365` often showed:

* More reviews
* Higher prices
* Stronger demand indicators

This may suggest higher occupancy rates or limited listing availability.

---

## 4. Smaller Hosts May Deliver Better Customer Experience

The analysis suggests that hosts managing fewer listings often receive stronger customer engagement.

One possible explanation is that smaller hosts may:

* Focus more on maintenance
* Provide better customer service
* Offer cleaner and more personalized experiences

Meanwhile, hosts managing large numbers of listings may face operational challenges that affect consistency.

---

## 5. Staten Island Shows Strong Customer Satisfaction Signals

Although Manhattan and Brooklyn appear to have the highest overall market demand, Staten Island listings received relatively high review activity compared to their lower prices.

This may indicate:

* Better perceived value for money
* Higher customer satisfaction
* Affordable private accommodations

However, review counts alone should not be treated as a perfect measurement of demand, since many customers do not leave reviews.

---

## 6. Listing Titles and Keywords May Influence Customer Interest

A text analysis of listing names revealed that highly reviewed listings frequently include descriptive and attractive keywords such as:

* private
* cozy
* luxury
* spacious
* near subway
* central
* clean

This suggests that detailed and informative listing titles may help attract more customer attention.

Listings mentioning:

* nearby attractions
* transportation access
* comfort
* privacy
* amenities

often appeared among highly reviewed properties.

---

# Business Insights

The analysis suggests that successful Airbnb listings in NYC are often associated with:

* Better privacy
* Strategic locations
* Detailed and attractive titles
* Accessibility to transportation and attractions
* Strong host management quality

Additionally, premium pricing appears sustainable in areas with strong tourism demand and desirable experiences.

---

# Conclusion

This analysis demonstrates that Airbnb market performance in New York City is influenced by a combination of:

* location
* privacy
* listing presentation
* pricing strategy
* host management quality
  
  ---
<img width="571" height="432" alt="image" src="https://github.com/user-attachments/assets/b82f2148-5154-4828-bc11-679ced8f7ebd" />
<img width="571" height="433" alt="image" src="https://github.com/user-attachments/assets/c3bfc72a-82f3-4a19-bd5a-6455e8179aa4" />
<img width="589" height="433" alt="image" src="https://github.com/user-attachments/assets/6a7361d2-07e6-48ff-b47a-2e566193a78d" />
<img width="571" height="433" alt="image" src="https://github.com/user-attachments/assets/a1615fe5-551a-4b20-b4d3-fa73fa770ea3" />
<img width="589" height="433" alt="image" src="https://github.com/user-attachments/assets/5db95d5a-d87e-4657-ade4-365f027daa01" />
<img width="571" height="433" alt="image" src="https://github.com/user-attachments/assets/06b4cc72-e32e-452b-87c1-d56d4169ea02" />

  ---
  
* Rather than relying only on averages, the project focused on understanding customer behavior and identifying the characteristics of successful listings.
* The findings may help hosts optimize their listings and support better business decisions in short-term rental marketplaces.


