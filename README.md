# MoodOn_Engage2022
![Homepage](/screenshots/img1.png)
## Inspiration

In today's world where everyone is striving for achievement, making a few poor decisions occasionally. As a result, **MoodOn** was designed to assist people in reduce stress by recommending movies and songs based on their emotions.

## How it Works

**MoodOn** is a facial expression recognition-based movie and music suggestion website that cheer up users and saves time while searching for a movie or song that matches their mood.
1. It recognizes facial expression based on the 6 categories i.e., angry, sad, fear,
    happy, surprise and neutral.
2. Based on the emotion it gives user two choices  either suggesting movies or songs.
3. If user wishes to watch movies/songs then a list of movies/songs matching their mood 
   are suggested with movie/songs images.
4. When user clicks on movie which he wishes to watch, they will be redirected to
    **IMDB** website and for songs it redirects them to **Spotify** website.

## Tech Stack Used
<img src="https://img.shields.io/badge/Python-ColourCode?logo=python&logoColor=ColorName&style=ShieldStyle" />  <img src="https://img.shields.io/badge/HTML-ColourCode?logo=HTML&logoColor=ColorName&style=ShieldStyle" />  <img src="https://img.shields.io/badge/CSS-ColourCode?logo=CSS&logoColor=ColorName&style=ShieldStyle" />  <img src="https://img.shields.io/badge/flask-ColourCode?logo=flask&logoColor=ColorName&style=ShieldStyle" />


**Python** is the programming language used to create the emotion recognition . CV2, TensorFlow, NumPy, matplotlib, and other libraries are also utilized. The model is build using the transfer learning approach for which MobileNet model is used. The FER-2013 dataset, which comprises around 35000 photos, was utilized for model training and validation. 
  This model is deployed on a website created with **HTML** and **CSS** using the **flask framework**. Based on the six emotions, a new dataset of movies and music was constructed. The data from movies and songs was utilized to create the various templates that correlate to various emotions. 

## Features

1. Emotion recognition - Recognizes the emotion of the user using webcam.
2. Recommend songs and movies - Recognizes user's mood and based on that shows
   classified songs and movies.
3. Contact - If user finds any problem can contact with us in provided three ways.
4. Login - User can create account and login in .
5. About - It tells about the project.

## Accomplishments that I'm proud of
Creating a project that is effective for the modern generation.Learnt a great deal about Python and different frameworks such as flask and its integration, many new libraries in Python.

## What I learned

I learnt about the transfer learning approach for the model, which assisted us in face identification, as well as how to develop basic web pages using HTML, CSS and how to deploy the model on the web using flask.

Screenshots

![emotion](/screenshots/img2.png)      ![contact](/screenshots/img3.png)
![login/signup](/screenshots/img4.png)  ![about](/screenshots/img5.png)

