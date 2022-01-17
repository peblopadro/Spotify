# ReadMe
![image_guy](https://user-images.githubusercontent.com/79945708/149636402-62dbf274-fae5-4c1f-bdcf-dd59071a4380.jpg)

A CRISP-DM process is outlined as follows:

**Business Understanding**

This repository contains a [notebook](https://github.com/peblopadro/Spotify/blob/main/Spotify_TopSongs.ipynb) with *exploratory data analysis* (EDA) of the most popular songs listened in Spotify over the 2010s. 

The analysis answers questions such as:
- Which song was the most poular each year and over the all decade?
- Who was the most popular artist?
- Which artist contributed with most amount of popular songs?
- Is there a common characteristic behind a popular song?

**Data Understanding**

The dataset used is from the pubicly available [Kaggle's competition](https://www.kaggle.com/leonardopena/top-spotify-songs-from-20102019-by-year/metadata).

**Prepare Data**

Given certain names having different characters from the english alhabet, either from artists as well as songs (e.g. Beyonc**è**), using pandas's 'read_csv' default `utf-8` encoding will show errors. It is shown in the notebook solutions to properly download it with the right encoding.

The data contains 12 features, including Beats-per-minute (the tempo of the song), Popularity score (based on Billboard rankings), Energy (i.e. the higher the score, the more energetic), a Danceability (the higher the score, the easier it is to dance to this song), “Speach-iness” (the higher the score the more spoken word the song contains), among others.

Also an analysis of shape, number of features and data samples, missing values and proper formating of the features was performed.

**Evaluation & Findings**

- *Top Genres by Year*: A Data table and a pie chart shows *dance pop* was the most porpular genre.

- *Danceable Scores by Genre*: Using a bar plot it is shown that Australian Hip Hop was the most danceable genre.

- *Artist With The Most Hits By Year*: Using pivoted table, it is shown Christina Aguilera was the artist with the most hits by year.

- *Average Length of a Song:* Using a lineplot it can be seen it has been decreasing over the decade, although at a small pace.

- *Most Popular Songs by Year and of the Decade:*  Using a pivoted table, it is shown Memories by Maroon 5 is the most popular song of the decade.

- *Artist and Songs with Most Lyrics:* Using a pivoted table, it is shown Justin Bieber is the artist with the most amount of lyrics among the popular songs, and LIttle Mix's *How Ya' Doing?* is the popular song with the most amount of lyrics.

- *Most Positive Mood Songs of the Decade*: Using a pivoted table, it is shown Austin Malone's *mmm yeah* is the song with the highest positive mood score.

- *Distribution of bpm*: Using a boxen plot, it is shown the distribution of bpm is fairly constant throughout the decade, ranging on average around the mid 120s.

- *Correlation Between Popularity and Features:* Using a heatmap, it different features are analyzed to see any positive or negative correlation between the popularity of a song and them.

- *Most Popular Artist of the Decade*: Using NLP's Word Cloud visualization tool, it is depicted that Katy Perry is the most popular artist of the decade.


**Documention**

A full report is published in [published in Medium](https://medium.com/@pedropablom/spotifys-top-songs-of-2010s-8938d8e96f95) showing all the findings.
