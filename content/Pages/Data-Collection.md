Title: Data-Collection
Date: 2024-05-13
Category: Python
Tags: pelican, python, dataviz, data-collection
Slug: data-collection
Authors: Julian Gutierrez

Initially for data collection & curation, the idea was to utilize the [SpotifyAPI](https://developer.spotify.com/documentation/web-api/), using a provided clientID it should have been a clean case of utilizing the API to scrape and obtain some information based on the proposed question of music trends and cultural changes. Through various hoops of trial and error and heartbreak, the realization of the limitations of the SpotifyAPI began to settle in. Spotify is very protective of the information that you may obtain using their API, and my original plan of utilizing the API quickly became a constraint to this project as opposed to a tool, for example the SpotifyAPI will not directly give you the top songs currently at the charts, instead one work around that I quickly found was that Spotify curates playlists based on top songs. One example is a Spotify playlist where the top 50 songs in the globe are put into one playlist, and through these spotify curated playlists I began to look into these playlists for information in where I could group top songs and genres within a year span. My next hurdle in my data collection was the fact that not all of these Spotify playlists were avaliable, I was only notibaly able to access the Top Hits from the years 2011, 2018, and 2019, and through some searching this is when I found my next breakthrough 

Through searching similar data set ideas on Kaggle, one user currated data set stood out to my mission, I had found a data set with every top 100 song from each year ranging from [2010-2019](https://www.kaggle.com/datasets/muhmores/spotify-top-100-songs-of-20152019/data), which included the missing playlists curated from Spotify in an excel file in which allowed me t use python to sort and visualize the data, giving me the missing playlists and gave me the ability to create 9 graphs that illustrate the trends in music. 

[![Screenshot-2024-05-14-at-6-58-49-AM.png](https://i.postimg.cc/52dHCWDh/Screenshot-2024-05-14-at-6-58-49-AM.png)](https://postimg.cc/LnD4cw9D)

Here is an example of the code that I used in order to go through the spreadsheet and curate graphs that are tailored to show the trends that will be dicussed in the analysis section.



