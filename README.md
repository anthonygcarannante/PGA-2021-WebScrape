# PGA-2021-WebScrape

This repository is an individual web scrape and ETL project. I wanted to pull professional golfer statistics for the 2021 season. This was a pretty straigthforward scrape. It primarily required Pandas to pull the statistics from the HTML tables and store them into Pandas DataFrames.

Technologies Used: Pandas, BeautifulSoup, HTML

## WebPage Preview

<img width="624" alt="Screen Shot 2021-07-05 at 3 19 35 PM" src="https://user-images.githubusercontent.com/79670978/124511562-760ef980-dda4-11eb-8a5f-1b027b574be3.png">

## Code Preview

This is a preview of the code involving pulling the top 5 leaders in each metric that is tracked on the ESPN website, cleaned and loaded into individual dataframes.

<img width="1003" alt="Screen Shot 2021-07-05 at 3 34 54 PM" src="https://user-images.githubusercontent.com/79670978/124512648-e159cb00-dda6-11eb-95e9-2c170afb9653.png">

<img width="989" alt="Screen Shot 2021-07-05 at 3 35 05 PM" src="https://user-images.githubusercontent.com/79670978/124512656-e454bb80-dda6-11eb-9af6-b573e792c698.png">

Once the top 5 leaders were sorted and organized, I pulled the full statistics table for all players on tour and loaded into one large dataframe. A for loop was required to sift through the webpages by changing the webpage URL.

<img width="1008" alt="Screen Shot 2021-07-05 at 3 52 55 PM" src="https://user-images.githubusercontent.com/79670978/124515189-cab67280-ddac-11eb-8389-16b69ca25952.png">

## Future Updates

I plan to update this project by potentially loading this into a SQL database as well as look for trends in these statistics among pro golfers on the PGA tour. I will also be pulling stats for previous PGA seasons.

### Contact Info
e: anthonygcarannante@gmail.com
