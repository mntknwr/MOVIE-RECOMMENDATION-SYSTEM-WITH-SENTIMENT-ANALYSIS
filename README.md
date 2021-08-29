# Movie Recommendation with Sentiment Analysis

![Python](https://img.shields.io/badge/Python-3.9-blueviolet)
![Framework](https://img.shields.io/badge/Framework-Flask-red)
![Frontend](https://img.shields.io/badge/Frontend-HTML/CSS/JS-green)
![API](https://img.shields.io/badge/API-TMDB-fcba03)

This web application offers all the requested movie's information, including an overview, genre, release date, rating, runtime, top cast, reviews, and suggested movies.

The movie information (title, genre, runtime, rating, poster, and so on) are retrieved using TMDB's API, https://www.themoviedb.org/documentation/api, and using the IMDB id of the movie in the API, I used beautifulsoup4 to web scrape the IMDB site and conduct sentiment analysis on the user reviews.

## How to get an API key?

Create an account at https://www.themoviedb.org/, then go to your account settings and click on the API link in the left hand sidebar to apply for an API key. If a website URL is requested, just state "NA" if you do not have one. Once your request is accepted, the API key will appear on your API sidebar.

## How to run this project?

1. Create a clone of this repository on your own machine.
2. All of datasets must be downloaded and the libraries listed in the requirements.txt file should be installed.
3. In the `static/recommend.js` file, replace YOUR API KEY in **both** locations (lines 23 and 43).
4. Open a command prompt in your project directory and type the command `python main.py` to execute the `main.py` file.
5. In the address box of your browser, enter http://127.0.0.1:5000/.
6. Hurray! That's it.

### Download the datasets from here 

1. [The Movies Dataset till 2016](https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset)
2. [The Movies Dataset till 2017](https://www.kaggle.com/rounakbanik/the-movies-dataset)
3. [List of movies in 2018](https://en.wikipedia.org/wiki/List_of_American_films_of_2018)
4. [List of movies in 2019](https://en.wikipedia.org/wiki/List_of_American_films_of_2019)
5. [List of movies in 2020](https://en.wikipedia.org/wiki/List_of_American_films_of_2020)

### Final Output
1. [Demo](https://www.movie-project.ml)

### Contact me
1. [Email](mailto:emailme@mn-tk-nwr.tech)
