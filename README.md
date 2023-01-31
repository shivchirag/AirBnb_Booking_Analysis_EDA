# AirBnb_Booking_Analysis_EDA

Hello, all. We have worked on the AirBnb Booking dataset of the year 2019. The dataset contains information of various hosts, their listings and the response of the users in terms of the number of reviews, when was the listing last reviewed etc.

We have tried to work on the data and get three things out of it:

a. We have tried to understand the user behaviour
b. We have tried to understand the hosts' behaviour
c. And most importantly, we have used those two to advice or suggest the stakeholders of AirBnb few points which when worked on will help drive the business in our humble opinion.

We hope that you like the project and we would like to listen to your thoughts on it. You can reach me at shivchirag1997@gmail.com

## Problem Statement

AirBnb is a hotel and room rental service provider. We have been provided with the dataset of the business from the city of New York and it looks like the dataset is of 2019. The dataset has information on the users, the hosts and the listings.

Using the dataset, we can provide insights that helps the businesses in many ways. We can provide marketing guidelines and also help the stakeholders understand the behaviour of users and the hosts, thus helping drive the business.

## Dataset

The dataset has 48895 records and 16 columns. There are no duplicate values, but there are values missing in four of the 16 columns.

**id :** Unique ID

**name :** Name of the listing

**host_id :** Unique Host ID

**host_name :** Unique Host Name

**neighbourhood_group :** Location

**neighbourhood :** Area

**latitude :** Latitude of the listing

**longitude :** Longitude of the listing

**room_type :** Type of the listing

**price :** Price of the listing

**minimum_nights :** Minimum nights to be paid for

**number_of_reviews :** Total no of reviews received

**last_review :** Date of the latest review received

**reviews_per_month :** Reviews recieved per month

**calculated_hosts_listings_count :** Total listings by host

**availibility_365 :** Availibility around the year

## Data Cleaning and Wrangling:

There were no duplicated values but there were null values to be treated. We removed the columns id, name and host_name as we didn't need them in our analysis.

We also replaced the 0 values in the price columns. To be as specific as we could, we used the median values for the room_type and the neighbourhood_group of every row that had price 0.

We divided the data as per the room_type column to ensure we have the right kind of data when we begin with our visualisation process.

Finally, we made a new column last_review_year. 

## EDA Process

We did an extensive analyis of the dataset using charts like heatmap, barplot, scatterplot, line plot and pie chart. These were used to do multiple univariate, bivariate and multivariate analysis and reach to the final set of advices/suggestions and the conclusions.

For more on the process and the results, would recommend to go through the project notebook uploaded and/or the final presentation prepared.
