# battle_of_the_neighborhoods (Coursera capstone project)
Where would be the best place to open a chinese restaurant in NY!


Read the blog at:
https://roydipta.medium.com/business-case-report-best-place-in-nyc-to-open-a-restaurant-d74d0298666f


INTRODUCTION:
NYC needs no introduction, but here’s some quick facts about the best city in the world! New York City is one of the most populous city in the United States with a population of about 8.39 million in 2020. It is a hub of diverse cultures combining all facets of the globe. The city is a major industrial center and the financial capital of the world. There are 5 boroughs in the city, and with such a large geographical area there is a lot of competition between companies. Thus there is a big challenge in figuring out the most ideal spots to open up a new business and maximizing profits. In this project, we’ll be focusing on opening up a Chinese restaurant as that’s one of the most popular cuisine in America according to the analysis done by Chefs Pencil using Google search data.
https://www.chefspencil.com/most-popular-ethnic-cuisines-in-america/
Business Problem:
Where can we open a Chinese Food Restaurant in the City of New York with the goal of maximizing customers and profit.
Target Audience:
Investors and developers who might be interested in getting into the commercial food industry. We are assuming these investors and developers have already done cost analysis and are willing to take the risk of a new business. All we are here to do is to provide a suggestion of where the business should be opened.
Data:
We used data from https://geo.nyu.edu/catalog/nyu_2451_34572 for a breakdown of all of the neighborhoods in NYC. The dataset includes the 5 boroughs, 306 neighborhoods and their latitude and longitude coordinates.
We also used Foursquare API calls to get information for restaurants in each of the neighborhoods. In these calls were the venue names, ratings, and the neighborhood of the restaurant.
Methodology:
1) Data will be collected from https://cocl.us/new_york_dataset and cleaned and processed into a dataframe.
2) FourSquare be used to locate all venues and then filtered by Chinese restaurants. Ratings, tips, and likes by users will be counted and added to the dataframe.
3) Data will be sorted based on rankings.
4) Finally, the data be will be visually assessed using graphing from Python libraries.
Results and Discussion:
First things first, we want to see the breakdown of neighborhoods in each borough. Looking at the graph below we can see that Queens has the highest amount of neighborhoods, followed by Brooklyn and then Manhattan. The reason we wanted to look into this is because we wanted to see the breakdown of how many neighborhoods there were per borough, and compare that to how many chinese restaurants were already in the neighborhood. This way we can minimize competition and have a better idea of where we should actually open up a restaurant.
We can visually see that there are the highest amounts of chinese restaurants in Queens, followed by Manhattan, then Brooklyn. We can see here that on average Manhattan has more restaurants per neighborhood then Brooklyn which means there’s less competition in Brooklyn.
