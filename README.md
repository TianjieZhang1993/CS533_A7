# CS533 A7
- name: TJ Zhang
- email: tjzhang@u.boisestate.edu
- This repository is mainly for the Assignment 7 in CS 533: Introduction to data science. I would like to thank Professor Michael Ekstrand for your teaching.


## Data source:

1. Movielens:

website: https://grouplens.org/datasets/movielens/

please download **MovieLens 25M Dataset**

2. TMDB: 

website: https://www.themoviedb.org/

3. IMDB:

website: https://www.imdb.com/interfaces/

we mainly use **title.crew.tsv.gz**, please download this file firstly.

## Files description:

**download.py:** This file is used to download the Movielens dataset and IMDB.

**mergedata.py:** This file is used to combine the Movielens dataset, TMDB and IMDB together to a movies.csv.

**preprocess_for_RQ1.py:** This file is used to preprocess the movies.csv to meet the requirement of Research Question 1.

**preprocess_for_RQ2.py:** This file is used to preprocess the movies.csv to meet the requirement of Research Question 2.

**functions.py:** This file contains some functions that would be used in jupyter notebook.

**research_question1.ipynb:** This file is used to Predict whether a movie is profitable.

**research_question2.ipynb:** This file is used to find if the ratings in Movielens and in TMDB are Consistent？.

## Run Order:
1. Create the environment with conda env create: 
```python 
conda env create -f environment.yml 
```
You can also update an environment to make sure it meets the current requirements in a file:
```python 
conda env update -f environment.yml
```
2. Using **download.py** to download the **MovieLens 25M Dataset** and **IMDB(title.crew.tsv.gz)** and unzip these files;
3. Run the **mergedata.py** to combine the Movielens dataset, TMDB and IMDB together to a movies.csv;
4. Run the **preprocess_for_RQ1.py** and **preprocess_for_RQ2.py** to get the preprocessed files for research_question1 and research_question2;
5. Run the **research_question1.ipynb** and **research_question2.ipynb** to see the data analysis of the movie data.


