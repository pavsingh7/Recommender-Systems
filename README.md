# Recommender Systems

> used to predict the "rating" or "preference" that a user would give to an item

A series of scripts and notebooks with resources pertaining to all things RecSys (recommender system). 

<img src="/img/recsys_cov.jpeg" width="450" height="200">

***
# Notebooks

## [Collaborative Filtering Recommender Systems in R](https://github.com/pavsingh7/Recommender-Systems/blob/main/Collaborative%20Filtering/recsys_cf.Rmd)

We introduce collaborative filtering for recommender systems. We slowly explain each method in CF - user-based and item-based collaborative filtering. We provide practical examples to get familiar with how the  methods work.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pavsingh7/Recommender-Systems/blob/master/Collaborative%20Filtering/recsys_cf.Rmd)

## [Collaborative Filtering Recommender Systems in Python](https://github.com/pavsingh7/Recommender-Systems/blob/main/Collaborative%20Filtering/recsys_cf.ipynb)

A python implementation of the the [first notebook](https://github.com/pavsingh7/Recommender-Systems/blob/main/recsys_cf.rmd). We do not go into great detail about how the methods work, as this is assumed knowledge. The details and explanations are found in the first notebook.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pavsingh7/Recommender-Systems/blob/master/Collaborative%20Filtering/recsys_cf.ipynb)


## [Content Based Filtering Recommender Systems](https://github.com/pavsingh7/Recommender-Systems/blob/main/Content%20Based%20Filtering/recsys_cb.ipynb)

A python implementation of the content based approach for recommender systems. The notebook also covers details and explanations for the code.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pavsingh7/Recommender-Systems/blob/master/Content%20Based%20Filtering/recsys_cb.ipynb)


## [Hybrid Recommender Systems](https://github.com/pavsingh7/Recommender-Systems/blob/main/recsys_cb.ipynb)

We look at ways in which we can combine two different recommender systems approaches to generate more comprehensive models with improved accuracy.

***
## Recommender Systems

A Recommender System, is a subclass of information filtering system that seeks to predict the "rating" or "preference" a user would give to an item. Recommender systems are utilized in a variety of areas, but are most commonly recognized as playlist generators for video and music services, product recommenders for online stores, or content recommenders for social media platforms.

    Recommend relevant items for users, based on their preference 

Current trends in recommender systems include the use of deep learning techniques, the incorporation of contextual information (such as location or time of day), and the use of interactive interfaces that allow users to provide feedback and help improve the recommendations being made.

## Types

There are several different types of recommender systems. Three popular frameworks include: 

- **Content-Based Recommenders**: These systems recommend items to a user based on their past preferences. For example, if a user has previously purchased a number of science fiction books, a content-based recommender might recommend additional science fiction books to them.

- **Collaborative Filtering Recommenders**: These systems take into account the preferences of multiple users when making recommendations. For example, if two users have both purchased a number of mystery novels and a number of science fiction books, a collaborative filtering recommender might recommend a science fiction book to one user and a mystery novel to the other user.

- **Hybrid Recommenders**: These systems use a combination of content-based and collaborative filtering techniques to make recommendations.


***
# References and Resources

The introductory notebooks for collaborative filtering follow the learnings of the course taken by [Ian Durbach](https://iandurbach.github.io) at the University of Cape Town. The remaining sources of information are cited appropriately within the respective notebooks. 

<table>
  <tr>
    <td>
      <img src="/img/recsys.png" width="275" height="220">
    </td>
    <td>
      <img src="/img/recsys_thumb.jpeg" width="280" height="220">
    </td>
</table>
