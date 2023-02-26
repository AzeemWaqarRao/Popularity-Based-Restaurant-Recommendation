# Popularity-Based-Restaurant-Recommendation

## Purpose:
This Notebook Recommends Restaurants based on popularity <br />

## Data:
1-We have a ratings data which contains ratings given to different restaurants by different users <br />
2-We have a cuisine data which contains cuisines of different restaurants <br />

## Libraries Used:
1-Pandas <br />
2-Numpy <br />

## Approach
1-From the ratings data we group the data by restaurant's ID <br />
2-Then we find the count of ratings for each restaurant <br />
3-Hence we will get a data frame with restaurants and their count of ratings <br />
4-Merge this data frame with most rated restaurants <br />
5-If we see Cuisine data, we will notice Mexican is the most offered Cuisine <br />
Hence we can recommend Most Rated Mexican Restaurants <br />
