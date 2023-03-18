---
layout: post
title: "Web Scraping"
author: Abby Wadsworth
description: Downloading and cleaning data about Pokémon
image: /assets/images/blog3a/adult.png
---

I remember when I was young, watching cartoons as a family with my big brother and sisters and one of the shows that was always my favorite was Pokémon. I started playing Pokémon Go recently, and I have become slightly obsessed. Because of this, I decided to look up data about different Pokémon in order to learn more as well as run analysis on the characteristics that differ from Pokémon to Pokémon.

One thing I am especially interested in how gender differs depending on the Pokémon. I found a data set that had the ratio of males per Pokémon type, which I thought was super interesting. I decided to research whether Pokémon that are more likely to be male are larger/heavier than those that are more likely to be female. I am also intrigued to see if the proportion of males differs from generation.

I found a [website](https://swhui.github.io/StatisticsinPokemon/datasets/) that had links to all these different types of data set that people have put together about Pokémon. I was able to download most of them through Kagle, so I decided to do that since the data was available.

First thing I did was download all the data sets that I was interested in, I started with four, though I ended up getting rid of one that had data I was less interested in. Since some of them were quite large, one had forty-two different variables! After downloading all of the data set an reading them into python, I went through and organized them by getting rid of columns that were repeats, since several of the graphs had similar variables that they measured.

As I was narrowing down the data sets, I decided that I didn’t need all of those variables in order to answer my research question about gender, so I decided to delete columns of variables that aren’t related to my research question, there were a lot of columns I went through and deleted them using the pandas function drop, which needs to have the column names, so it took quite a bit of time

I had to erase extra rows from one of the datasets that had multiple rows for Pokémon as well as their mega versions. Afterwards I made sure that all the Pokémon data sets had the same variable name for the Pokédex number, which was found in all the different data frames. This made it so I could put all the datasets together quite easily using the merge function in pandas on the Pokédex variable.

It is so cool to actually look at data that I am passionate about. I love stats, but if there’s something so satisfying about putting together my own data set which I have never done before now. There is so much data that you can find, especially using the internet. Be willing to ask questions and getting data to answer them.

I am still cleaning my dataset, since there are 649 rows with 21 different variables, but I am excited to see where this goes. I am excited to keep looking at this data set and see where it goes. Till next time, when I am going to be doing some exploratory data analysis on this data set and sharing visuals that I will be making using python.


![Figure](https://raw.githubusercontent.com/abbywadsworth/my386blog/main/assets/images/blog3a/baby.jpg)