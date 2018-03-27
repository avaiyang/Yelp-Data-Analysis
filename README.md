# Yelp-Data-Analysis
## About the Yelp Dataset

> 4.1M reviews and 947K tips by 1M users for 144K businesses

> 1.1M business attributes, e.g., hours, parking availability, ambience.

> Aggregated check-ins over time for each of the 125K businesses

> 200,000 pictures from the included businesses

## Analysis
1. Summarize the number of unique reviewers by US city, by business category. That is, count the
unique reviewers by city, by business.

2. Rank all cities by # of stars descending, for each category

3. What is the average rank (# stars) for businesses within 15 km of Edinburgh Castle, Scotland, by type of business (category)? Note: A business with more than one category will be listed more than once, once per category,
```
Center: Edinburg Castle, Scotland, 
UK Latitude/Longitude: 55.9469753, -3.2096308
```
The bounding circle for this problem is a 15 km radius. A business falls in the region if it’s coordinates are within the circle.

4. Rank reviewers in Q3 by their number of reviews. For the top 10 reviewers, show their average number of stars, by category.

5. For the top 10 and bottom 10 category Food businesses in Q3, (in terms of stars), summarize star rating for reviews in January through May only.
