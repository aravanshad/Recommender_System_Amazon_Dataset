# Recommender_System_Amazon_Dataset

I have built a recommender system on Amazon's recommendation dataset available at https://www.kaggle.com/qwikfix/amazon-recommendation-dataset/data
If you are a data scientist, the first thing comes to your mind when you hear the word "Amazon" is `Recommender System`. Our objective was to implement two recommendation system techniques including `Collaborative Filtering` and `Content-Based Filtering` and evaluate their performance, with respect to a base non-personalized model (Popularity model), for the task of providing personalized recommendations to the users.

### Dataset

This dataset consists of reviews of fine foods from amazon. The data span a period of more than 10 years, including all ~500,000 reviews up to October 2012. Reviews include product and user information, ratings, and a plain text review. It also includes reviews from all other Amazon categories.

Data includes:
- Reviews from Oct 1999 - Oct 2012
- 568,454 reviews
- 256,059 users
- 74,258 products
- 260 users with > 50 reviews

### Install

This project requires **Python 3.6** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [pyti](https://github.com/kylejusticemagnuson/pyti)
- [brew](http://brew.readthedocs.io/en/latest/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [imbalanced-learn](http://contrib.scikit-learn.org/imbalanced-learn/stable/)
- [keras](https://keras.io)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

We recommend installing [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains most of the necessary libraries and software for this project. 

### Code

The code is provided in the `Notebooks` folder. The CSV files and `Clfs` folder (pool of trained classifiers) are not included due to the size limitation. 

### Run

In a terminal or command window, navigate to the top-level project directory `Notebooks/` (that contains this README) and run one of the following commands:

```bash
ipython notebook {name of notebook file}.ipynb
```  
or
```bash
jupyter notebook {name of notebook file}.ipynb
```

This will open the iPython Notebook software and project file in your browser.

### Data

This dataset consists of 1-min stock data from a [post](https://github.com/Finance-And-ML/US-Stock-Intraday-Dataset) at Github for a time period from 06/06/2017 to 07/14/2017 (approximately 10,000 data points). A more recent dataset (from 2017-07-18 to 2017-07-21) from the same Github post (approximately 1,500 data points) was downloaded for back testing.


