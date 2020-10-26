# python-notebooks

## List of Sample Python notebooks to upload

1. A notebook focussed on testing the outputs of a Random Number Generator: comes with an * .ipynb and a * .csv which is read into the file at the top. 

2. A python notebook which analyses an experiment statistically and outputs a load of data: comes with one * .ipynb and two * .csvs which are read in at the top.

3. A Big data python notebook which imports a compiled .py file in the same file/tree and then runs the functions from that file (I can’t remember what it does, it’s from a Data Science course I did at general assembly)

## Notes on how to call functions hosted in a * .py file in the same folder:
https://problemsolvingwithpython.com/07-Functions-and-Modules/07.05-Calling-Functions-from-Other-Files/

## Stackoverflow article on how to use code from an external file in a python notebook:
https://stackoverflow.com/questions/56481126/how-to-use-code-from-external-python-files-in-jupyter-notebook

## Instructions for using iPython Notebooks with PyCharm:
1. https://www.jetbrains.com/help/pycharm/jupyter-notebook-support.html#get-started
2. https://www.jetbrains.com/help/pycharm/running-jupyter-notebook-cells.html

## List of notebooks found in 00_WordVectorExamples

#### 01_spark_examples_py
Inside the examples folder for python, under a sub-folder called ML, there are a punch of example python scripts, one includes vectorising and a few other things.
Recommended files to look at include:
1. word2vec_example.py
2. count_vectorizer_example.py
3. clustering.py

#### 2_latent-variables-and-natural-language-processing
A python notebook which looks at using “bag of words” and a few other approaches at high level to vectorise words, again for the purpose of NLP
* The notebook is called “lesson-16-codealong.ipynb”

### Useful as it covers:
##### from sklearn.feature_extraction.text import CountVectorizer
AND
##### from gensim.models.ldamodel import LdaModel
##### from gensim.matutils import Sparse2Corpus
and also covers “bag od words”
-- #Transform the text into the bag-of-words (bow) space using our vectorizer
##### new_bow = vectorizer.transform(new_text)

#### 3_nlp_tagging_vectorising
A set of notebooks I have using `NLTK` to compute `TF-IDF`, which is pretty simple but informative, using a package called `Gensim`, and it has a written out function for creating bigrams etc, which is similar to the approach suggested in the first article (the one which links to the colaboratory notebook)
* The notebook is called “Simple Tagging”


## Useful materials focussed on vectorising words for the purpose of either NLP or fuzzy matching

### Vectorising article 1:
1. Article: https://towardsdatascience.com/fuzzy-matching-at-scale-84f2bfd0c536
2. Matching Notebook on colaboratory: https://colab.research.google.com/drive/1qhBwDRitrgapNhyaHGxCW8uKK5SWJblW

### Alternative matrix vectorising/word processing system on GitHub that I got recommended:
1. Article: https://medium.com/wbaa/https-medium-com-ingwbaa-boosting-selection-of-the-most-similar-entities-in-large-scale-datasets-450b3242e618
2. GitHub Repo: https://github.com/ing-bank/sparse_dot_topn