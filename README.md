# Top100_US_Cities
- assignment for data engineering intership

**Environment:** python 3.7
**Packages:** re/numpy/pandas/BeautifulSoup/urllib

**The main dataset** comes from https://en.wikipedia.org/wiki/List_of_United_States_cities_by_population

**Another 100 webpages** are extracted from the main dataset

There are **4 steps** in this small projects:
1. Scrape and clean the main dataset
2. Extract the wikipage for each city from the main dataset
3. By using the wikipages to extract the official website of each city
4. Combine all the data into the dataframe and stored as csv file
