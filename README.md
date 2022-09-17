# Task-3 GRIP @ THE SPARKS FOUNDATION
Aim: To perform EDA on a sample store and get insights from the same. Furthermore, we visualize it, create a dashboard, and generate a business report

The foremost step is to import all the relevant libraries.

Now, load the dataset

Now- we try to understand the dataset which we have.

1) We understand the columns which we have in our data. Looking at the same, we have 13 columns in our dataset.
2) 'Ship Mode', 'Segment', 'Country', 'City', 'State', 'Postal Code','Region', 'Category', 'Sub-Category', 'Sales', 'Quantity', 'Discount','Profit'. These are the columns in our dataset.
3) out of all these columns observed above, the ship mode is unnecessary, thus we need to drop it. Hence, we drop it
4) We now check for any null values in our dataset, there are no null values.

*These steps were essential for data pre-processing.

Now - we check the unique values under each column to get an idea about our data.
*INSIGHTS

1- There are 531 cities in our dataset. i.e : out of 19,000(app) cities in the US, The business is well expanded to over 531 cities.
2 - There are 49 states in our dataset, i.e : out of 50 states in the US, The business is well expanded to over 49 states.
3 - The main products of the company are : 'Furniture', 'Office Supplies', 'Technology'
4 - There are 3 categories nd 17 sub categories.

['Bookcases' 'Chairs' 'Labels' 'Tables' 'Storage' 'Furnishings' 'Art', 'Phones' 'Binders' 'Appliances' 'Paper' 'Accessories' 'Envelopes','Fasteners' 'Supplies' 'Machines' 'Copiers'] are the sub categories.
 
 Max number of orders are from - The NY city, least : Manhattan,Glenview, Missouri City,Rochester Hills,Palatine Hence, these cities requires an area of improvement.
 
 Similarily, max orders are from the state : California , least are from : Montana, South Dakota, Vermont, District of Columbia, Maine, North Dakota, West Virginia, Wyoming            
 
 the business could be well expanded in the south region.
 
 The business flourishes in terms of the products like : 'office supples' but needs improvement in 'technology'.
 
 thus, as seen above, these were the general insights from the data.
 
 NOW- WE look at the section of the data which requires an area of improvement
 
 out of 9994 observations, 1871 are loss - producing. i.e about 18.7% of the dataset are loss producing.
 
 We plot a pairplot for segments of data and thus, conclude on its basis.
 
 Then, we calculate the top 10 cities and states , categories, sub- categories with losses
 
 Thus, we go on further to visualize the data and we draw conclusions on the basis of the same
