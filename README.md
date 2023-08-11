## Content 📋
The basic idea of analyzing the Zomato dataset is to get a fair idea about the factors affec􀆟ng the establishment of different types of restaurants at different places in Bengaluru, aggregate ra􀆟ng of each restaurant.
Bengaluru being one such city has more than 12,000 restaurants with restaurants serving dishes from all over the world. With each day new restaurants opening the industry hasn’t been saturated yet and the demand is increasing day by day.
In spite of increasing demand, it however has become difficult for new restaurants to compete with established restaurants. Most of them serving the same food. Bengaluru being an IT capital of India. Most of the people here are dependent mainly on the restaurant food as they don’t have 􀆟me to cook for themselves. With such an overwhelming demand of restaurants it has therefore become important to study the demography of a loca􀆟on.


## DATA
• Source of Data: The data is available on one of open source pla􀆞orm – kaggle.com and downloaded here- [Zomato Bangalore Restaurants](https://www.kaggle.com/himanshupoddar/zomato-bangalore-restaurants/download)
• Data Collec􀆟on: The data was scraped from Zomato website and collected in two phases. In Phase I, the URLs, names, and addresses of restaurants visible on the front page of Zomato were extracted and recorded in a CSV file, simplifying the later individual data extrac􀆟on process. In Phase II, data for each restaurant and category was scraped individually.
• Data Content: obtaining 15 variables such as online order, book_table, rate, votes, phone, loca􀆟on, rest_type, dish_liked, cuisines, approx_cost (for two people), reviews_list, and menu_item.
• Data Profile:
1. The dataset contains 51717 rows and 17 columns; a􀅌er data Quality check, it has dataset contains 49853 rows and 10 columns
2. The missing Value have been replaced with or calcula􀆟ng avg of the column.
3. Deleted some null values

## Limitation and ethics
1. Limitation: The contains a lot of missing values and also contains unnecessary informa􀆟on. The Data contains many errors in typing.
2. Ethical issue: The data contains some personal Informa􀆟on so ge􀆫ng rid of those columns for security purposes.

## Questions
• What kind of a food is more popular in a locality
• What are the popular restaurants by loca􀆟on
• Cheapest, highest rated and largely voted restaurants
• Is there a rela􀆟on between cuisine, loca􀆟on and the cost?
• Expensive, Highest rated and largely voted.
• Which locality of that city serves those cuisines with maximum number of restaurants
• The needs of people who are striving to get the best cuisine of the neighborhood
• Is a par􀆟cular neighborhood famous for its own kind of food.
