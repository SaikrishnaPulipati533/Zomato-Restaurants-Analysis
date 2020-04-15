# Zomato-Restaurants-Analysis

This project works on the Zomato dataset is to get a fair idea about the factors affecting the aggregate rating of each restaurant, the establishment of different types of the restaurant at different places



Dataset description:

The dataset contains the details of restaurants in Bengaluru, India. This dataset is based on Zomato, an Indian restaurant search and discovery service [1]. The dataset contains 51717 rows and 17 columns. This information was fetched based on the shape of the dataset. There are various anomalies in the data like columns containing null values, mismatched information, trailing spaces, and invalid characters etc.

There are only one integer based attribute i.e. votes and all other attributes are object type.

The description of the attributes is given below:

url is the url of each restaurant. It is a unique identifier in the dataset.
address is the physical address of the restaurant.
name is the name of the restaurants. They are repeated in the dataset as one location can have multiple branches of the same restaurant.
online_order column has the values of Yes and No. It signifies if the restaurant accepts the online order or not.
book_table also has the value of Yes and No. The value represents if the restaurant has an option to book the table.
rate is the average rate of the restaurant out of 5.
votes signifies the number of votes counted for the rating of the restaurant.
phone column contains the phone number of the restaurant.
location is the physical location of the restaurant.
rest_type explains the type of the restaurant like casual dining, quick bites etc.
dish_liked contains a list of dishes liked at the restaurant.
cuisines is the list of cuisines offered at the restaurant.
Approx_cost(for two people) contains the approximate cost of food at the restaurant for two people.
reviews_list contains the reviews given by the customer for the restaurant. It also has the individual rate given by the customer.
menu_item contains the list of menu items from the menu list of the restaurant.
listed_in(type) is the type of meals or food types provided at the restaurant. The unique values are: 'Buffet', 'Cafes', 'Delivery', 'Desserts', 'Dine-out', 'Drinks & nightlife', 'Pubs and bars'.
listed_in(city) signifies the location where the restaurant is located.
