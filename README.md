# Introduction

Exploration of pixalized coffee. View at [coffee2themax.cortadita.com](coffee2themax.cortadita.com).

Adapted from Koalas To The Max. View the source code of the original on [GitHub](https://github.com/vogievetsky/KoalasToTheMax).

Powered by [Mike Bostock](http://bost.ocks.org/mike/)'s [D3](http://d3js.org/)

# Changes

This ReadMe focuses on just the changes in this fork versus the original.

## Runs on Google App Engine

Coffee To The Max runs on Google App Engine. An app.yaml file replaces the server config file in the original source.

## Coffee images replace koala images

I like to drink coffee, and also take pictures, especially when there's a nice ambiance or neat latte art. One day I realized just how many coffee pictures I have. It's a veritable collection and it reminds me of all the places I've been. These are a few of my favorites. I request you use your own images and not reproduce these. 

## Custom image option gone

This time it's all about the coffee. The image-server.php file is gone along with any supporting files and javascript.

## Remove Google Analytics

I removed the Google Analytics tracking code in the original, which included the site's ID. I may replace with my own code eventually, but for now I just wanted to avoid contaminating their GA reports.

## Other extraneous code

I removed a subfolder called "test", which contained just one image named with Cyrillic characters. Google App Engine was warning that these characters were not supported. Also gone is a directory called .idea, a file called "stuff" and the rick-rolling "astley.jpg". Sorry, Rick! Just want to keep things minimal.
