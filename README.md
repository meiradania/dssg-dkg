# Data Science for Social Good - Deutsche Krebsgesellschaft

To run the notebooks, anaconda installation is recommended: includes jupyter notebook, python 2.7 and all libraries except gensim: https://docs.continuum.io/anaconda/install

## Python Notebooks Description:

* 1_parsing_xml.ipynb - read xml exported from Reference Manager into dataframe.

* 2_features_extraction.ipynb - transform full title string into numerical representation, by removing stopwords, lowering case and converting into dictionary.

* 3_features_transformation.ipynb - transform documents from the dictionary vector representation into TF-IDF representation, and save as numpy array format.

* 4_classification.ipynb - use TF-IDF representation of full title to classify documents into useful/not useful. Algorithms: logistic regression and k-means.




#### Python libraries used:
* pandas: http://pandas.pydata.org/
* nltk: https://www.nltk.org/
* gensim: https://radimrehurek.com/gensim/
* numpy: http://www.numpy.org/
* scipy: https://www.scipy.org/
* sklearn: http://scikit-learn.org/
