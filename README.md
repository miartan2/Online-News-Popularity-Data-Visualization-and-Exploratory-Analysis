# Exploring the Features of Online News Articles That Drive Popularity
This project investigates what makes certain online news articles go viral. Using a dataset of 500 Mashable articles, the analysis explores how structural features (length, multimedia, publication timing) and content‑based features (topic, sentiment, subjectivity, keywords) relate to article popularity, measured by number of shares.

The full interactive report is available in the HTML file included in this repository.

# Data Source
This project uses the Online News Popularity Dataset from the UCI Machine Learning Repository.

Fernandes, K., Vinagre, P., & Cortez, P. (2015). A Proactive Intelligent Decision Support System for Predicting the Popularity of Online News. UCI Machine Learning Repository.

# Tools
- R Markdown for narrative analysis
- tidyverse for data wrangling
- ggplot2 and plotly for visualizations
- gganimate for animated graphics
- Shiny for interactive exploration

# Key Visualizations
- Distribution of Article Shares: A density plot showing the right-skewed nature of article popularity
- Shares by Day of the Week: Interactive jitter + summary plot revealing modest weekday differences, with Saturday showing slightly higher average shares
- Topic Popularity: Animated bar chart comparing average vs. total shares across topics (Lifestyle stands out in average shares)
- Title and Content Length: Embedded Shiny app exploring whether shorter or longer articles perform better
- Weekday and Topic Interaction: Interactive line plot showing how topic performance varies across the week
- Sentiment and Subjectivity: Two Shiny apps examining how emotional tone and subjectivity relate to shares
- Multimedia Effects: Boxplots comparing shares for articles with vs. without images or videos
- Keyword Performance: A connected dot plot showing how “best” vs. “worst” keywords influence shares across topics

# Insights
- Topic matters - Lifestyle, World, Business, and Tech articles consistently achieve higher engagement
- Keyword quality is a strong predictor - Articles with high‑impact keywords show substantially higher shares
- Moderate emotional tone performs best - Articles with balanced polarity and subjectivity tend to be shared more
- Structural features matter less - Title length, content length, and multimedia presence show weak or inconsistent relationships with shares
- Virality is multifactorial - No single feature guarantees popularity; instead, combinations of topic, tone, and keyword alignment drive engagement

# Viewing the Project
Open the HTML file (`Features-of-Online-News-Popularity.html`).

For interactive Shiny components, visit:
- https://miartan.shinyapps.io/stat3280app/
- https://miartan.shinyapps.io/stat3280app2/
- https://miartan.shinyapps.io/stat3280app3/
