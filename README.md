# Mission to Mars Web-Scraping Project

The goal of this project was to gather insights into Mars missions, weather patterns, and other relevant information by scraping data from various Mars-related websites and to organize and analyze the data.

## Data Sources
The source of the data for this project includes:

Mars News Website: The data for scraping titles and preview text from Mars news articles is sourced from the <a href="https://mars.nasa.gov/news/">Mars NASA news website</a>.

Mars Temperature Data Site: The data for scraping and analyzing Mars weather data is sourced from the <a href="https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html">Mars Temperature Data website</a>

## Skills Used 
Python, Web Scraping 

## Actions
For this project, the first step involved scraping data from the Mars Temperature Data Site. To achieve this, I utilized Splinter for automated browsing to visit the website and BeautifulSoup to extract data from the HTML table. After obtaining the data, I assembled it into a Pandas DataFrame, ensuring appropriate column names were used.

With the data prepared, I proceeded to analyze various aspects of Martian weather patterns. This included determining the number of months present on Mars and calculating the Martian days' worth of data available in the dataset. I also delved into the coldest and warmest months based on minimum daily temperatures, as well as examined the months with the lowest and highest atmospheric pressure.

To better understand the relationship between terrestrial days and Martian years, I visualized the data by plotting bar charts for average temperatures and atmospheric pressure by month. Finally, I estimated the duration of a Martian year based on temperature fluctuations, revealing insights into the Martian calendar and its alignment with Earth time units.

## Results 
