# LCS_Project
My goal is to leverage LCS data to solve potential issues within the competition and help pinpoint solutions. 

## Introduction
Watching the Riot Games' LCS and wondering what the Esports organizations do for analysis and I ask myself, "What can I develop and create that can help an team do better before and after a match?" 

Analysts can analyze a match and determine optimal strategies based on the match in question. I personally feel this reactive methodology for team support is required but is not everything. Data Science is a fairly new field (< 3 years), especially in the realm of esports.

## Problem
Every team has a top, jungler, mid, bot, and support position. In order to create the optimal champion picks to compete against the opposing organization picks is based on statistics and inuition. My question is can I use the data of previous matches to predict ban and picks in the correct order?

This is a difficult, complex problem, but I believe that meta, player, team, and more all contribute to specific champion compositions. And if these choices happen, what is the likeilihood of winning the match?

This question has many individual components that can be useful on its own. 

### Plan for solution
1. Develop a method/model that can accurately predict Ban Picks in order 
2. Develop a method/model that can accurately predict Opposing Team's champion picks in order
3. Develop a method/model that can predict within confidence the ideal propensity to win a match based on the champion composition of both teams
