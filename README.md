# CS533_A7
- name: TJ Zhang
- email: tjzhang@u.boisestate.edu


describes the repository: what are the scripts and notebooks, what do they do, and in what order do they need to be run.

- Dataset source:

### *Movielens:* 

website: https://grouplens.org/datasets/movielens/

please download **MovieLens 25M Dataset**

### *TMDB:* 

website: https://www.themoviedb.org/

### *IMDB:* 

website: https://www.imdb.com/interfaces/

we mainly use **title.crew.tsv.gz**, please download this file firstly.

## Scripts description:

**mergedata.py:** This file is used to combine the Movielens dataset, TMDB and IMDB together to a movies.csv

**preprocess_for_RQ1.py:** This file is used to preprocess the movies.csv to meet the requirement of Research Question 1.

**preprocess_for_RQ2.py:** This file is used to preprocess the movies.csv to meet the requirement of Research Question 2.

**functions.py:** This file is used to act as some functions that would be used in jupyter notebook.

## notebook description:

**research_question1:** This file is used to Predict whether a movie is profitable.

**research_question2:** This file is used to find if the ratings in Movielens and in TMDB are Consistent？.


