# Meme Generator Data Wrangling and Analysis
Data modeling, data wrangling (database creation), data analysis (language-identification and bootstrap sentiment-analysis), and visualization (with Tableau) of 56,000 Meme Generator memes archived by the Library of Congress. 

## Objective
This repo grew out of graduate project work for Dr. James Howison at the University of Texas at Austin, evolved into visualization project work for Andrea Cato, and is now dedicated to practicing (and preserving) my data engineering and visualization.

Most of this engineering and data work is coded with Python in Jupyter Notebooks, directories will include datasets and code files. Code include comments to walk through different steps of wrangling and analysis.

## Gallery

## Datasources

1. [Library of Congress' Meme Generator dataset](https://www.loc.gov/item/2018655320/) - a dataset created on May 5, 2018, from Library of Congress web crawls of http://memegenerator.net/ and accessioned to the Library's Web Cultures Web Archive. It includes data for 57,652 memes. Meme Generator allows users to create and share image macros (featuring a picture, or artwork, superimposed with text) in the style of popular internet memes. Captions were broken into unigrams. No lemmatization was performed.

![Screen%20Shot%202020-11-25%20at%204.22.02%20PM.png](attachment:Screen%20Shot%202020-11-25%20at%204.22.02%20PM.png)

2. [Hong Kong University of Science and Technology’s Knowledge Computation Group hate speech dataset](https://github.com/HKUST-KnowComp/MLMA_hate_speech) – contains hate speech indicator words in English, French, and Arabic.

![Screen%20Shot%202020-11-25%20at%204.49.25%20PM.png](attachment:Screen%20Shot%202020-11-25%20at%204.49.25%20PM.png)

3. [Stonybrook University Data Science Lab's international sentiment lexicons](https://sites.google.com/site/datascienceslab/projects/multilingualsentiment) (also avaiable on [Kaggle](https://www.kaggle.com/rtatman/sentiment-lexicons-for-81-languages)) – sets collected by Yanqing Chen and Steven Skiena<sup>1</sup> of both "positive" and "negative" lexicons for 82 languages.

<sup>1</sup>Chen, Y., & Skiena, S. (2014). "Building Sentiment Lexicons for All Major Languages.". In *ACL* (2) (pp. 383-389).)




