## Codes related to constructing the data for "Technology cluster dynamics and network" paper

<p>&nbsp;</p>

### Identifying relevant articles for the potential definition of technology clusters

Most of the Wikipedia articles are irrelevant for the match with patents: articles about people, books, movies, geographical locations, etc. 
__relevant_articles_part1.ipynb__ and __relevant_articles_part2.ipynb__ suggest several ways how to identify and eliminate these irrelevant articles to facilitate the match.

* __relevant_articles_part1.ipynb__ uses information available from the titles, text and type of the infoboxes get rid of irrelevant articles

* __relevant_articles_part2.ipynb__ uses information in patents to identify potentially relevant articles

<p>&nbsp;</p>

### Match between patents and Wikipedia articles
__patent_article_match.ipynb__ matches patents to their most similar Wikipedia articles by text using Cosine similarity

<p>&nbsp;</p>

### Technology cluster network construction
__network_builder.ipynb__  builds a weighted network of technology clusters

<p>&nbsp;</p>

### Libraries needed:
* re
* numpy
* spacy
* pandas
* nltk
* geotext
* string
* scipy.sparse
* sklearn.feature_extraction.text
* sparse_dot_topn.sparse_dot_topn


