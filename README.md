# web_scraping-and-analysis
Part 1
First thing I did in this project was to inspect the page to identify which elements to scrape. Also, I create a Beautiful Soup object and use it to extract text elements from the website. 
I extracted the titles and preview text of the news articles that scraped and stored the scraping results in Python data structures as follows. I also store each title-and -preview pair in python dicitionary two keys :title and preview. 
Part2
First, I used automated browsing to visit the Mars Temperature Data Site and inspected the page to identify which elements to scrape.
Then created a Beautiful Soup object and use it to scrape the data in the HTML table. I also asssebled the scraped data into a Pandas Data Frame. The column names are also extracted from the table headers to label the data appropriately. After collecting the data, it is assembled into a Pandas DataFrame for further manipulation.
Data Analysis and Visualization:
By analyzing the dataset, it's determined that there are 12 months on Mars, similar to Earth. The dataset contains weather records for 1867 Martian days (sols). Also, to find the coldest and warmest months, the average minimum temperature for each Martian month is calculated and plotted as a bar chart. The coldest months are typically months 3 and 4, while the warmest months are around month 8. Atmospheric Pressure Analysis: Similarly, the average atmospheric pressure for each month is computed and visualized. The months with the highest pressure tend to be around month 9, while the lowest pressure is observed in months 5 and 6.Year Length Estimation: By plotting the minimum temperature over the terrestrial days (Earth days), a visual estimate of the Martian year length can be made. This helps estimate how many Earth days it takes for Mars to complete one orbit around the Sun.

I worked on this project with the help of the Homeworks and Xpert Learning AI tool. 

