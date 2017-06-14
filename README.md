Python  | Numpy | Pandas | Statsmodels | Sci-Kit Learn
--------|-----|-----|---------|------
[![PyPI](https://img.shields.io/badge/python-3.5-blue.svg)]() | [![PyPI version](https://badge.fury.io/py/numpy.svg)](https://badge.fury.io/py/numpy) | [![PyPI version](https://badge.fury.io/py/pandas.svg)](https://badge.fury.io/py/pandas) | [![PyPI version](https://badge.fury.io/py/statsmodels.svg)](https://badge.fury.io/py/statsmodels) |  [![PyPI version](https://badge.fury.io/py/scikit-learn.svg)](https://badge.fury.io/py/scikit-learn)

Repo update in progress! Slides live [here](https://docs.google.com/presentation/d/1RJU3pMKxl3LNKHNtG5fEU00aM4DNMtNPZ-2LRxuMa2k/edit?usp=sharing).  **Code coming soon**

# Beer Advocate Rating Predictor

Applied ensembles of regression algorithms on craft beer datasets to predict BeerAdvocate ratings.

## Problem Statement
- Though the beer industry as a whole may not have changed in market size in recent years, strangely enough there’s an increase in the production of craft beer, import beer, and export craft beers,  Why?
- Turns out, the craft beer market is steadily gaining, compared with other, lagging beer categories.
  - Light beer fell from a 47.3% market share in 2014 to a 45.5% share in 2015.
  - Projections for Big Beer in 2016 are more of the same: gradual decline.  Big brands are under threat.

![](https://s3-us-west-2.amazonaws.com/brewersassoc/wp-content/uploads/2009/08/Sales_2016-1.jpg)
  
### Why bother predicting the next hit beers?
- Craft drinkers are turning away from the name-brand craft beers towards smaller, newer, edgier breweries.
- If craft breweries are to continue growing, they have to continue satisfying the *evolving consumer palate.*

**Producing the new beers that customers enjoy begins with accurately predicting the popular craft beers of the future.**

## Data
- **Craftcans.com**: Scraped CraftCans.com database for their 2692 craft canned beers and 550 different breweries.
  - Features: Beer name, Style, Size sold (ounces), Alcohol by volume (ABV), IBU’s (International Bitterness Units), Brewer name, Brewer city, Brewer state

- **BeerAdvocate.com**: Scraped the BeerAdvocate.com beer ranking tables for their 4000+ craft beer ratings.
  - Features: Features: Beer name, Brewer, Brewer state, Volume of ratings, Volume of reviews, Beer Weighted Rank
  - Why BA?  Neither advertisers, sponsorships, or industry relationships influence the opinions expressed by BeerAdvocate and its founders.  They have specific Industry Posting Rules that prevent the rating or reviewing of places or beers that users own or are affiliated with.  The only biases that might exists come from the community of users and their demographics.


## Analytical Approach

Will better explain the questions guiding analyses and a summary of the methods involved.

- Linear Regression
- Ridge Regression
- Lasso
- CART
- Extratrees
- RandomForestRegress
- AdaBoostedTrees
- GradBoostedTrees
- GridSearch



## Tool Stack

- Jupyter notebook
- Python 3.5
- BeautifulSoup4, Selenium
- Statsmodels
- Sci-kit Learn
- Matplotlib, Seaborn

Might include step by step series of examples that tell you have to get a development env running

## Visuals [In Development]
- See slide deck.  Graphs coming soon

## Conclusions
More to come.  Will explain insights gleaned, model evaluation, or patterns in visualization.

## Future Work

- feature engineering
- xgboost
- hyperparameter tuning


## Author

* [**Andrew Tom**](https://github.com/Atomahawk)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments & Inspirations

* Jean-Nicholas Hould on Scraping for Craft Beers: http://www.jeannicholashould.com/python-web-scraping-tutorial-for-craft-beers.html
* Charlie Bamforth and Beer Research at UC Davis: http://faculty.bftv.ucdavis.edu/fst/Bamforth/research.html
