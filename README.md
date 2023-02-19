# EDA-Airbnb
## **Project Type**    - EDA
#### **Contribution**    - Team
#### **Name of Team Members -** 
1.   Shrikant Narayan Patole.
2.   Nilay Hemant Dhage.

## **Project Description**
Since 2008, guests and hosts have used Airbnb to expand on travelling possibilities and present a more unique, personalised way of experiencing the world. Today, Airbnb became one of a kind service that is used and recognized by the whole world. Data analysis on millions of listings provided through Airbnb is a crucial factor for the company. These millions of listings generate a lot of data - data that can be analysed and used for security, business decisions, understanding of customers' and providers' (hosts) behaviour and performance on the platform, guiding marketing initiatives, implementation of innovative additional services and much more. This dataset has around 49,000 observations in it with 16 columns and it is a mix of categorical and numeric values. Explore and analyse the data to discover key understandings.

## **Variable Description:**

1. id: Unique ID
2. name: name of the listing
3. host_id: Unique host ID
4. host_name: name of the host
5. neighbourhood_group: location
6. neighbourhood: area
7. latitude: latitude range
8. longitude: longitude range
9. room_type: type of listing
10. price: price of listing
11. minimum_nights: minimum nights to be paid for
12. number_of_reviews: number of reviews
13. last_review: content of the last review
14. reviews_per_month: number of reviews per month
15. calculated_host_listings_count: total count
16. availability_365: number of days when listing is available for booking

## **Analyzes done:**
* **Univariate analysis**
1. highest no of airbnb owned by a host
2. Number of hotel listing depending on location
3. Most popular neighbourhood preferred by customers
* **Bivariate Analysis** 
4. Host with highest reviews
5. Room types preferred by customers in each neighbourhood group
6. Trend of number of reviews with respect to price of the listings

* **Multivariate Analysis**
7. Average price of neighbourhood group depending on room type
8. Availability of rooms in neighbourhood groups depending on their type
9. Minimum nights spent depending on the neighbourhood and room type
10. Latitude and longitude relation with neighbourhood group
11. Co-relation heatmap

## Useful Insights found from Data Visualization:
* Top 3 hosts have almost more than 100 properties hosted.So company can provide some extra facilities,rewards to them which will help in maintaining good relations.
* As more customers may prefer to stay in Brooklyn and Manhattan,company can increase the no of properties in these areas.
* Company should try to attract more customer to Staten Island and Bronx.
* Company should provide more facilities to customers in top 10 busiest neighbourhoods as it may have high impact on no of customers.
* Company can take feedback from the highly reviewed hosts and can implement them for other hosts to improve their service.
* Even though properties in Bronx,Queens and Staten Island are more available,people still prefer to visit Manhattan and Brooklyn.It may be because of less no of properties and their comparatively higher prices in Staten Island and Bronx.
* Company should try to reduce the prices of shared rooms across all neighbourhoods.They seem to be overvalued in comparison to private rooms.
* As availability of rooms is positive point for Staten Island,Bronx and Queens.Steps can be taken to increase the no of visits in these areas.
* Properties in Manhattan and Brooklyn are more crowded and preferred.So company should try to increase availability of rooms in these areas.
* Low priced rooms are more likely to be visited and price factor effects on the no of reviews i.e popularity of property.
* price,no of reviews,availability,minimum nights spent are independent in terms of correlation with each other.All these factors are highly dependent on values such as neighbourhood,neighbourhood groups,room type.
