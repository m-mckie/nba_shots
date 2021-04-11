# Introduction

In basketball, one of the most widely used metrics to evaluate a player's quality is Field Goal Percentage, which is the ratio of Shots Made to Shots Attempted. With technological advancements allowing for player tracking in the NBA, I will incorporate new player tracking data into a model to expand upon Field Goal Percentage with the goal of improving how players are evaluated.

General Overview of Process

Step 1 - Data Collection

Originally the NBA allowed public access to all their tracking data from each game when they instituted player tracking to start the 2015 season. However, it's safe to assume they realized the value in this data and changed how the data was presented as from 2016 on they only provided aggregated player tracking data which wasn't useful for me. The aggregated data wouldn't help me as I wanted to investigate all shots on a per shot basis. This was unexpected when originally starting this examination however it still peaked my interest. I was able to find shot data from the 2015 season on github and supplemented it with individual player data, and shot data scraped from NBA.com

There are two notebooks that contain my original collection and merging of data. They are found in the notebooks titled 2. Capstone Scrapers, and 3. Capstone Data Collection.

Step 2 - Data Processing, Cleaning & Exploratory Data Analysis

Notebooks 4. Capstone Preprocessing & 5. Capstone Features go through the necessary steps before I can instantiate and evaluate models.

Step 3 - Constructing and Evaluating Models

Notebook 6. Capstone Modelling 3.0 contains my final iteration of my modelling process

Step 4 - Interpret, Communicate, Visualize and Report

The next steps of my Capstone are to aggregate the data as I now have the probability of each individual shot going in. I'd first want to aggregate the data based on shot area to find league averages for shot probability/ quality. Then, I'd aggregate by player which is where the real value lies in this process. It would enable me to evaluate player shooting skill at a higher level than just field goal percentage. With that information I'd be able to compare to see if a player is above or below league average when it comes to shooting difficult shots. My hypothesis is that the better the player is, the better they will be at making harder shots. In theory there are players that slip through the cracks when evaluating a player's skill based on field goal percentage. If a player takes harder shots or attracts more attention from the defence their 40% field goal percentage is much more valuable than a player who the defence doesn't guard and shoots 40%.
