Module 11 Challenge

This new assignment consists of two technical products. You will submit the following deliverables:
*Deliverable 1: Scrape titles and preview text from Mars news articles.
*Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.


# Part 1: Scrape Titles and Preview Text from Mars News
In this section, you’ll use Python and SQLAlchemy to do a basic climate analysis and data exploration of your climate database
* Use automated browsing to visit the Mars news siteLinks to an external site.. Inspect the page to identify which elements to scrape.
* Create a Beautiful Soup object and use it to extract text elements from the website.
* Extract the titles and preview text of the news articles that you scraped..

# Part 2: Scrape and Analyze Mars Weather Data
* Use automated browsing to visit the Mars Temperature Data SiteLinks to an external site.. Inspect the page to identify which elements to scrape. Note that the URL is https://static.bc-edx.com/data/web/mars_facts/temperature.html.
* Create a Beautiful Soup object and use it to scrape the data in the HTML table. Note that this can also be achieved by using the Pandas read_html function. However, use Beautiful Soup here to continue sharpening your web scraping skills.
* Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website. 
* Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.
* Analyze your dataset by using Pandas functions to answer the following questions:
1. How many months exist on Mars?
2. How many Martian (and not Earth) days worth of data exist in the scraped dataset?
3. What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
Find the average minimum daily temperature for all of the months.
Plot the results as a bar chart.
4. Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
Find the average daily atmospheric pressure of all the months.
Plot the results as a bar chart.
5. About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
Consider how many days elapse on Earth in the time that Mars circles the Sun once.
Visually estimate the result by plotting the daily minimum temperature.
* Export the DataFrame to a CSV file.