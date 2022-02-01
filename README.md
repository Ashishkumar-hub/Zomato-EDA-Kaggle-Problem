# Zomato EDA and Data Visualization 

### About the dataset - Background checkup
The basic idea of analyzing the Zomato dataset is to get a fair idea about the factors affecting the establishment
of different types of restaurant at different places in Bengaluru, aggregate rating of each restaurant, Bengaluru
being one such city has more than 12,000 restaurants with restaurants serving dishes from all over the world.
With each day new restaurants opening the industry has’nt been saturated yet and the demand is increasing
day by day. Inspite of increasing demand it however has become difficult for new restaurants to compete with
established restaurants. Most of them serving the same food. Bengaluru being an IT capital of India. Most of
the people here are dependent mainly on the restaurant food as they don’t have time to cook for themselves.
With such an overwhelming demand of restaurants it has therefore become important to study the demography
of a location. What kind of a food is more popular in a locality. Do the entire locality loves vegetarian food.
If yes then is that locality populated by a particular sect of people for eg. Jain, Marwaris, Gujaratis who are
mostly vegetarian. These kind of analysis can be done using the data, by studying the factors such as
• Location of the restaurant
• Approx Price of food
• Theme based restaurant or not
• Which locality of that city serves that cuisines with maximum number of restaurants
• The needs of people who are striving to get the best cuisine of the neighborhood
• Is a particular neighborhood famous for its own kind of food.

“Just so that you have a good meal the next time you step out”

The data is accurate to that available on the zomato website until 15 March 2019.
The data was scraped from Zomato in two phase. After going through the structure of the website I found that for each neighborhood there are 6-7 category of restaurants viz. Buffet, Cafes, Delivery, Desserts, Dine-out, Drinks & nightlife, Pubs and bars

### Dataset LinK:
This dataset was taken from kaggle below is the link to dataset
[Dataset-Zomato](https://www.kaggle.com/himanshupoddar/zomato-bangalore-restaurants)

### The Following task were performed :
- Loading the dataset: Load the data and import the libraries.
- Data Cleaning:
  - Deleting redundant columns.
  - Renaming the columns.
  - Dropping duplicates.
  - Cleaning individual columns.
  - Remove the NaN values from the dataset
  - Some Transformations

### Regression Analysis
- Linear Regression
- Decision Tree Regression
- Random Forest Regression

### Data Visualization: 
Using plots to find relations between the features.
- Restaurants delivering Online or not
- Restaurants allowing table booking or not
- Table booking Rate vs Rate
- Best Location
- Relation between Location and Rating
- Restaurant Type
- Gaussian Rest type and Rating
- Types of Services
- Relation between Type and Rating
- Cost of Restuarant
- No. of restaurants in a Location
- Restaurant type
- Most famous restaurant chains in Bengaluru

## Result: 
- Got the best accuracy for Extra tree regressor.
- EDA was done sucessfully and various insights were dwarn shown in notebook.
- Libraries used Matplotlib, Seaborn, Pandas, Numpy
[Click here to see Kaggle Notebook](https://www.kaggle.com/ashish12350/zomato)
