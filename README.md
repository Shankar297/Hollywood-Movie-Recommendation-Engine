# Hollywood Movie Recommendation Engine
The main goal of this project is to recommend the 5 movies based on user interest.

## Table of Content
  * [Demo](#demo)
  * [Problem Statement](#problem-statement)
  * [Approach](#approach)
  * [Technologies Used](#technologies-used)
  * [Installation](#installation)
  * [Deployement on Heroku](#deployement-on-heroku)
  * [Detailed Project Reports](#detailed-project-reports)
  * [Bugs & Logs](#bugs--logs)
  * [Contributors](#contributors)

## Demo
Link: [https://hollywood-movie-recommendor.herokuapp.com/](https://hollywood-movie-recommendor.herokuapp.com/)

![movie-recommedation](https://user-images.githubusercontent.com/76767335/171601030-fca3739b-99b9-4255-aed1-88362eee3c79.gif)


## Problem Statement
Movie recommendation system is one of the top research areas, currently. Due to the impact of high internet speeds, multimedia has become one of the best entertainments. bulid a movie recommendation engine that recommend five movies based on user movie selected movie.

## Approach
Data Exploration : Exploring dataset using pandas, numpy.

Feature Engineering : Removed missing values and created new features as per insights.

Pickle File : created pickle file as per need.

Building web app : Building web app using python.

User Interface & deployment :  Created an UI that shows the output.
                          After that I have deployed project on heroku.
## Technologies Used
 
   1. Python 
   2. Pandas
   3. Numpy
   4. Sklearn(CountVectorizer, cosine_similarity)
   5. Steamlit

## Dataset
[Download here](https://github.com/Shankar297/Hollywood-Movie-Recommendation-Engine/blob/master/tmdb_5000_credits.csv)


## Installation
Click here to install [python](https://www.python.org/downloads/). To install the required packages and libraries, run this pip command in the project directory after cloning the repository:
```bash
git clone https://github.com/Shankar297/Hollywood-Movie-Recommendation-Engine.git
```

```bash
pip install -r requirements.txt
```
If pip is not already installed, Follow this [link](https://pip.pypa.io/en/stable/installation/)

## Deployement on Heroku
Create a virtual app on Heroku website. You can either connect your github profile or download cli to manually deploy this project.
Follow the instruction given on [Heroku Documentation](https://devcenter.heroku.com/articles/getting-started-with-python) to deploy a web app.

## Bugs & Logs

1. If you find a bug, kindly open an issue and it will be addressed as early as possible.
2. Under localhost, logging is performed for all the actions and its stored onto logs.txt file
3. When the app is deployed on heroku, logs can be viewed on  heroku dashboard or CLI.

## Contributors
  [Shankar Wagh](https://github.com/Shankar297)

