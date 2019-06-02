# Beer_Recommender_CF
Beer Recommender System using Collaborative Filtering with Surprise &amp; sk-learn

### Beer Recommender System using Collaborative Filtering (item-item similarity)
The goal of this project was to create a recommender system that will take a beer name as an input and return the top N recommendations based on item similiarity. Content based recommendations was explored in a different notebook but the goal was to return recommendations that are varied and not just more of the same (which is what the content-base recommender would do). For example, if I like IPA beers I want to also explore non-IPA beers that may have similar charteristics but are different enough to be categorized as a different class of beer.

The Data:

* 56 subcategories of beer  
* 4964 unique beers  
* ~88K unique users  
* ~1.4M user-review pairings  
  
Data was scraped from a popular beer review website: https://www.beeradvocate.com/

Main Tools:  
Surprise Library - http://surpriselib.com/  
scikit-learn: https://scikit-learn.org/stable/
