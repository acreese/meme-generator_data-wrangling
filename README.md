# Meme Generator Data Wrangling and Analysis
Data modeling, data wrangling (database creation), data analysis (language-identification and bootstrap sentiment-analysis), and visualization (via Tableau) of 56,000 Meme Generator memes archived by the Library of Congress. 

## Objective

This repo grew out of graduate project work for Dr. James Howison at the University of Texas at Austin, evolved into visualization project work for Andrea Cato.

Most of this data engineering and wrangling is coded with SQL and Python inside Jupyter Notebooks.  Futher analysis and visualization is done with Tableau. Directories will include datasets and code files. Notebooks include notes and comments walking through different steps of wrangling and analysis.

## Problem Statement

...

## Gallery

[Interact with the dashboard on TableauPublic](https://public.tableau.com/views/MemeGeneratorLanguageandSentiment/FinalDraftDashboard2?:language=en-US&:display_count=n&:origin=viz_share_link)

![Meme sentiment and language visualization with Tableau](assets/meme_dash.png)

## Datasources

1. [Library of Congress' Meme Generator dataset](https://www.loc.gov/item/2018655320/) - a dataset created on May 5, 2018, from Library of Congress web crawls of http://memegenerator.net/ and accessioned to the Library's Web Cultures Web Archive. It includes data for 57,652 memes. Meme Generator allows users to create and share image macros (featuring a picture, or artwork, superimposed with text) in the style of popular internet memes. Captions were broken into unigrams. No lemmatization was performed.

2. [Hong Kong University of Science and Technology’s Knowledge Computation Group hate speech dataset](https://github.com/HKUST-KnowComp/MLMA_hate_speech) – contains hate speech indicator words in English, French, and Arabic.

3. [Stonybrook University Data Science Lab's international sentiment lexicons](https://sites.google.com/site/datascienceslab/projects/multilingualsentiment) (also avaiable on [Kaggle](https://www.kaggle.com/rtatman/sentiment-lexicons-for-81-languages)) – sets collected by Yanqing Chen and Steven Skiena ([2014 paper](https://www.semanticscholar.org/paper/Building-Sentiment-Lexicons-for-All-Major-Languages-Chen-Skiena/c5e3b065e352a93d8754b86baaf8ec20bf81a5c3)) of both "positive" and "negative" lexicons for 82 languages.

## Data Modeling




