# Congressional Data Scraper

I wrote this so I could get the data necessary for my Political Science Senior Thesis.

## Feature Summary

The scraper grabs roll call votes in a given Congressional session, codes them as a numeric matrix, then uses Singular Value Decomposition to represent high-dimensional distances in voting record as 2 dimensions.
This allows us to plot each Congressional session (with politicians clustered generally by party, due to similar voting record), but it also allows us to find the Root Mean Squared Error of each party.

Once we have the party RMSE values, we record that in a dataframe and repeat the process for the next Congressional session.
