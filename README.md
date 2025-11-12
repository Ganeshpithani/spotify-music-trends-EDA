# spotify-music-trends-EDA
Exploratory Data Analysis on Spotify Daily Charts using Python and Web Scraping
#  Spotify Music Trends - Exploratory Data Analysis

This project analyzes global Spotify chart data collected through web scraping.  
The goal is to explore song rankings, streams, and country-level trends.

---

##  Project Overview
- Scraped data from [kworb.net/spotify](https://kworb.net/spotify)
- Cleaned and processed data using Pandas & Regex
- Performed EDA with Matplotlib and Seaborn
- Visualized music trends across 7 countries

---

##  Dataset Details
| Column | Description |
|---------|-------------|
| Rank | Song position on the chart |
| Song | Song title |
| Artist | Artist name |
| Streams | Daily stream count |
| Days | Number of days on chart |
| Country | Chart country |
| Change | Rank change from previous day |

---

##  Key Visualizations
- Distribution of Streams
- Pie Chart of Total Streams by Country
- Top 10 Artists by Average Streams
- Streams vs Rank (Scatterplot)
- Correlation Heatmap

---

##  Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- BeautifulSoup (Web Scraping)
