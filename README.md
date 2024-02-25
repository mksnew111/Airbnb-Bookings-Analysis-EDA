#  Project Name:- Airbnb-Bookings-Analysis-EDA
# Contribution:- Individual
# Submitted By:- Mukesh Kumar Sah

# Project Summery:-
Airbnb is an online marketplace since 2008, which connects people who want to rent their homes with people who
are looking for accommodations in a particular location.The company ,which is based in San Francisco,
does not own any of the property listings, but it receives commissions from each booking like a broker.Nowadays, 
Airbnb became one of a kind service that is used and recognized by the whole world.Data analysts become a crucial factor
for the company that provided thousands of listings through Airbnb. These listings generate a lot of data that can 
be analyzed and used for security,business decisions, understanding of customers and providers behavior on the platform, 
guiding marketing initiatives, and much more.
In this project I do analysis on 2019 website data regarding listing on website, compare prices, analysis host data,
distribution of room type,avalability of room in whole year etc. I analysis data and provide different visulisation charts,different business insights
using python language. I use numpy library for creating data array that helps to analysis such big data.
we also use panda library which offers data structures and operations for manipulating numerical tables.

# Data Summery: - 
id - This contains unique numerical id of listing.
name - This contains name of Home/Appartment with few specification.
host_id - Id number that identifies the host.
host_name - This contain name of the host.
neighbourhood_group - This contain main regions of the New York city.
neighbourhood - This contains near by famous location of Room.
latitude - This contains geographical location of Room on map.
longitude - This contains geographical location of Room on map.
room_type - This contains different types of Room.
price - The price for one night
minimum_nights - Minimum amount of nights to book the place
number_of_reviews - Number of reviews received
last_review - Date of the last review
reviews_per_month - Amount of reviews per month
calculated_host_listings_count - Number of properties available on Airbnb owned by the host
availability_365 - Number of days of availability within 365 day

# In this Airbnb dataset, we have 16 columns/attributes and 48895 observations.
# Conclusion
1.	Entire home/apt room type has the highest number of listing of 51.97%,followed by 45.66% of private room and sharaed room is the   
    least listing room type at only 2.37% in total.

2.	Private room has the most prefered room type in neighbourhood location except Manhattan where Entire home/apt more prefered.

3. The shared rooms is found minimum number in every neighbourhood location.

4. Michael possesses the highest number of properties among all hosts.

5. Manhattum is the most exensive region when we compare the other neighborhood groups.On the other hand, the least expensive region is 
   Bronx.

6.	The most expensive room type across all neighbourhood groups is the entire home/apartment.

7. Shared Room is most economical room type in all neighbourhood groups.

8.	Minimum Price is almost equal in every neighbourhood groups.

