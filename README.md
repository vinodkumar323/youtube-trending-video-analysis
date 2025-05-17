# YouTube Trending Video Analytics :

A data science project to uncover patterns in trending YouTube videos across multiple countries using Python, Tableau, and YouTube Data API.

-> Objective

Analyze trending videos from different regions to identify:
- Most popular video categories
- Regional viewing habits
- Sentiment trends in video titles
- Optimal publishing times

-> Tools & Technologies:

- Python: Data cleaning, analysis, and visualizations
- Libraries: `pandas`, `matplotlib`, `seaborn`, `textblob`, `tqdm`
- YouTube Data API v3: Real-time trending video data collection
- SQL (Pandas equivalent): Category-wise view ranking
- Tableau: Interactive dashboard for storytelling

-> Data Collection:

Trending videos were fetched from the following countries:
- 🇺🇸 United States
- 🇮🇳 India
- 🇵🇰 Pakistan
- 🇷🇺 Russia
- 🇫🇷 France
- 🇮🇹 Italy
- 🇩🇪 Germany

Features collected:
- Video title, channel name, category
- Views, likes, dislikes, comment count
- Publish time, country code


->Data Analysis:

Key metrics created:
- `like_ratio` = likes / (likes + dislikes)
- `comment_ratio` = comment count / views
- `title_sentiment` = sentiment polarity (TextBlob)

-> Visualizations:

- Views by day of week** and hour of day
- Top channels and most viewed categories
- Correlation heatmap among engagement metrics
- Sentiment polarity vs viewership

->Tableau Dashboard:

Interactive dashboard includes:
- Pie chart: Share of views by category
- Bar chart: Top trending channels
- Line plot: Views by hour
- Region-wise genre comparison

-> Key Findings:

- Positive titles slightly boost engagement
- Evenings and weekends are peak trending times
- Rockstar Games, Netflix, and music channels dominate global trends

-> Future Scope:

-> Incorporate **historical trend analysis** for seasonal insights
-> Apply **advanced NLP models** for deeper sentiment understanding
-> Integrate **engagement metrics** like watch time and shares
