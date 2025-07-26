# :earth_americas: GDP dashboard template

A simple Streamlit app showing the GDP of different countries in the world.

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://gdp-dashboard-template.streamlit.app/)

### How to run it on your own machine

1. Install the requirements

   ```
   $ pip install -r requirements.txt
   ```

2. Run the app

   ```
   $ streamlit run streamlit_app.py
   ```

# Visualizing Global Media Trends: Movies & TV (1947–2025)

 **Project Overview**  
Built interactive dashboards using Tableau and Streamlit to explore international weekend box office performance (Feb–March 2025) and global TV show popularity (1947–2025). Data was scraped and compiled to help streaming services make data-driven, globally inclusive content decisions.

## 👥 Team
Katie Leedom, Arohi, Isabella, Ira, Rohitha

## Goals
- Highlight international media trends often overlooked by U.S.-centric streaming services.
- Empower content teams to select globally successful films and shows.
- Build a user-friendly dashboard for visual storytelling using real-world data.

## Technologies Used
- Python (web scraping with BeautifulSoup)
- Tableau Public (visualization)
- Streamlit (interactive dashboard front-end)
- Pandas, CSV for data formatting

## Methodology
- **Movies**: Scraped Box Office Mojo’s international weekend gross tables (2025), extracting:
  - Country/Area  
  - Weekend dates  
  - Number of releases  
  - Top release per country  
  - Distributor  
  - Weekend gross earnings  
- **TV Shows**: Used Tableau Web Connector to analyze global TV show metadata (vote count, release year, origin country) from 1947–2025.
- Built separate Tableau dashboards for movies and TV shows.
- Integrated into a Streamlit app using screenshots and external dashboard links.

## Key Insights

### Movie Trends
- **South Korea** was the highest-grossing region during Feb–March 2025.
- *"Mickey 7"* earned the highest weekend gross globally.
- Major distributors like **Lotte Entertainment** and **Toho** held strong market share.

###TV Show Trends
- Strong correlation between vote count and average rating.
- In **Canada**, one of the most popular shows was French-language — emphasizing the need for cultural and linguistic diversity.
- U.S. shows dominated in vote count, but global trends varied significantly.
  
## 📉 Challenges
- **Box Office Mojo** had no export option — data had to be scraped from HTML.
- **Streamlit Free Tier** does not support full Tableau dashboard embedding.
- Workaround: Used screenshots with redirect buttons to full dashboards.

## Files
- `streamlit_app.py`: Streamlit front-end with visuals and buttons
- `movies_data.csv`: Scraped movie data
- `eda_movie.ipynb`: Preliminary movie data exploration and visualization
- `tv_dashboard_link.txt`: TV dashboard Tableau links
- `images/`: Dashboard screenshots used in Streamlit app

## Next Steps
- Upgrade to paid Tableau plan to allow direct embedding in Streamlit.
- Add interactive filters (genre, language, year).
- Integrate streaming performance metrics (e.g., from Netflix or Disney+) for deeper insights.

