# Navajo Nation Water Quality
Final Project Submssion
Jaden Redhair - jadenkr@stanford.edu

NTUA is a utility company on the Navajo Nation that reports water quality across the Navajo Nation in various communities. My question is how can I take that data and make predictions about the amount of Arsenic that is in the water supplies given the other elements present like Chlorine and Copper for example.

My process for getting the data is as follows:

Scraping data : I use colab to download the pdfs from the NTUA website that reports the water quality.
Cleaning data : I then convert the pdfs to text and parse the text for the chemicals present and their associated measurements to put into a dataframe.
Location collecting : After I have the NTUA data, I get longitudes, latitudes and altitudes from Google given the town and state the water samples are from. Adding them to the dataframe.

Caviet:
Before presentations I had lost my Machine Learning notebook so I had to redo it. In my revision, I found better combinations to lower the RMSE. I got it to almost half my original RMSE from the presentation! 
