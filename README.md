# California Hotel Business Strategy
Building a web analytics model to deduce strategies for improving hotel performance based on hotel pricing, location, and initial investments employing data from ‘TripAdvisor’

This project is a part of MGMT 59000 - Web Data Analytics course.

Python Notebook Files List
--------------------------
1. Scraping Hotels in California.ipynb

This code scrapes the data for all hotels in California from Tripadvisor and saves it to ScrapedHotels.csv file.

2. Scraping Reviews of Top 10 Hotels.ipynb

This code scrapes the reviews data for top 10 hotels in California from Tripadvisor and saves it to 10 reviews csv files.

3. Code.ipynb

This code contains all the analysis on both the hotel data and reviews data obtained by scraping.


CSV Files List
--------------
1. ScrapedHotels.csv
2. hamptoninnreviews.csv
3. hollywoodhotelreviews.csv
4. hollywoodrooseveltreviews.csv
5. hotelcorquereviews.csv
6. hotelemblumreviews.csv
7. howardjohnsonreviews.csv
8. shorecliffeviews.csv
9. shorehotelreviews.csv
10. theanaheimreviews.csv
11. montereyplazareviews.csv


Dependencies
------------
1. Scraping Hotels in California.ipynb

Libraries Needed - numpy, pandas, time, BeautifulSoup, selenium, urllib, requests, random, warnings
Files Needed - chromedriver.exe in the same folder as the ipynb file

2. Scraping Reviews of Top 10 Hotels.ipynb

Libraries Needed - numpy, pandas, time, BeautifulSoup, selenium, urllib, requests, random, warnings, json
Files Needed - chromedriver.exe in the same folder as the ipynb file downloaded from https://chromedriver.chromium.org/downloads

3. Code.ipynb

Libraries Needed - numpy, pandas, statsmodels.api, scipy.stats, nltk, sklearn, gensim, textblob, seaborn, matplotlib, random, warnings
Files Needed - 
	1. ScrapedHotels.csv
	2. hamptoninnreviews.csv
	3. hollywoodhotelreviews.csv
	4. hollywoodrooseveltreviews.csv
	5. hotelcorquereviews.csv
	6. hotelemblumreviews.csv
	7. howardjohnsonreviews.csv
	8. shorecliffeviews.csv
	9. shorehotelreviews.csv
	10. theanaheimreviews.csv
	11. montereyplazareviews.csv


