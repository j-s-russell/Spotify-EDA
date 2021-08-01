# Spotify - Exploratory Data Analysis
---
## Background
* This is my first data analytics project, an exploratory data analysis of song data from 1922 to 2021. This comes from a Kaggle dataset compiled by Yamac Eren Ay, who scraped data of around 600,000 songs from the Spotify Web API. My music playlists include songs from several different eras, so I decided to analyze trends between different time periods to see how music has evolved over the last few decades and what genres have gained or lost popularity.
---
## Data
* The dataset includes 15 attributes, all shown in the correlation matrix below:

![](/images/corr_matrix.png)


* This project analyzes the attributes for different time periods of music, so we focus on the features that have the strongest correlation with the year feature:

![](/images/lineplot.png)

* Around 1950 - 1960, significant trends appeared in many of these variables, namely instrumentalness, energy, and acousticness. By taking the mean of these variables by each year, we can visualize how the characteristics of popular music changed over time - where these attributes were increasing/decreasing at the greatest rate, where they were less relevant, and where they peaked:

![](/images/energy.png)
![](/images/loudness.png)
![](/images/acousticness.png)

* There are fewer songs in the dataset during the early 1900's, so there is much more variation in these attributes during earlier years. Near the second half of the century, however, the energy, loudness, and acousticness attributes all show a significant relationship with the year. By the year 2010, energy and loudness had peaked, while acousticness had reached a minimum.
