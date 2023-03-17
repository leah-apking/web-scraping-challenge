# web-scraping-challenge

This challenge involved extracting information from two websites with Splinter for automated browsing and BeautifulSoup for HTML parsing. 

### Part 1: Mars News

For part one I used Splinter and chromedriver to create a beautiful soup object containing the text found on the Mars News Website. I used the inspector tool to dig through the HTML code and find the tags required to pull the information needed. The title and article previews for each article were stored in python dictionaries.

### Part 2: Mars Weather Data

This part of the challenge again included creating a beautiful soup object containing the data found in the table on the Mars weather data website. I used the same method as in part one to find the HTML tags required to extract the data. However, despite seeking out many resources, I decided to use Pandas read_html function in place of BeautifulSoup and web scrapping, in the spirit of simple is better than complex. Once in a DataFrame, I cast each column to its appropriate data type.

Finally, I analyzed the data set and determined the number of months on Mars and how many Martian days were contained in the data. Grouping the data by month I created two bar charts, one showing the average minimum temperature by month and the other showing atmospheric pressure on Mars by month. To estimate the number of Earth days there are in a Martian year, I calculated the number of Earth days in a single month and multiplied the result by 12.

