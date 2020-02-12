---
layout: post
title:      "CLI Project blog"
date:       2020-02-12 01:59:59 +0000
permalink:  cli_project_blog
---


This project is one of the tougher projects that I have done in quite some time.  I don't normally like to come up with something from complete scratch with very few guidlines.  This freedom bothered me for some time and I had to sit and sift through what I was going to do.  I hope that this process gets quicker as I go along with the coding program.

This project asks us to develop a cli, or command line interface, for anything that we choose.  It just stipulates that we have to give the user at least one set of choices and be able to give inforamtion of the choice from data that is pulled from the internet.  Since I am not very creative, I decided to look at a few of the suggestions within the project guidelines.  I found type i a zip code and list movies and that is what I chose.

I initially tried to scrape the fandango website because it was the first site that came up with a zipcode searchable movie system.  I tried scraping the data and was able to get a lot of the information but there was no discernable structure that I could break down to have everything about a theater and then the movies with them.  I don't remember now exactly why I decided to switch sites, but I do remember that structure was the main problem.  I then found IMDB website.  Finding how to break down the HTML so that I could seperate the theaters and then the movies.

I decided to use 4 different classes.  One for each: cli, theater, movie, scraper.  I used the theater to keep ahold of the movies they played.  I then used the movies to hold the movie times.
