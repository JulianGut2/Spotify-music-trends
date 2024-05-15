Title: Introduction
Date: 2024-05-13
Category: Python
Tags: pelican, python, kaggle, music, dataviz
Slug: Introduction
Authors: Julian Gutierrez

The association between music and culture is an idea that has been around for centuries, music is one of the closest ties associated with cultural norms and views. One way that cultural shifts and norms can be viewed is by analyzing music trends, to see if there is an association between the time of year and music trends in order to better understand cultural shifts throughout the year. This can be important to understanding how the time of year can correlate with how people might feel about a certain type of music as well as recognizing trends that may appear depending on the season. This has been studied countless times for example, scholars at the [Univeristy of Minnesota](https://open.lib.umn.edu/mediaandculture/chapter/6-3-the-reciprocal-nature-of-music-and-culture/#:~:text=For%20example%2C%20policies%20on%20immigration,people%20feel%20about%20those%20policies.) have shown that culture affects what kind music is created and music affects how different cultures are viewed. As a person who loves listening to music, and loves looking at data this was something that I was passionate about learning: being able to understand music trends has plenty of uses, from being able to help make data driven decisions all the way to just simply understanding the human behavior this topic is something that can be beneficial to investigate. The main method that was essential to navigate this question was the Spotify developer API, which granted access to database information on spotify statistics, this was my initial plan, however, one big constraint that lead me to changing how I approached this project was that the Spotify API provided very limited information, for example, the API will not directly pull the top songs globally at this moment, however, spotify does provide a playlist named **“Global Top 50”**, which gives us a rough estimate of what is popular at this moment. 

This drastically changed how I approached my project, as I thought the API would be more liberal with the information that you could obtain, so the direction of my project changed, instead of seeing changes throughout the season of any given year I instead opted for viewing the changes of song trends yearly as it was easier to obtain information that was general based on a year span as opposed to monthly. However, the biggest defining factor in how I analyzed the trends was finding a kaggle data that correlated exactly what I was looking for, and through scraping and visualizing through a curated spreadsheet, I was able to notice interesting trends.