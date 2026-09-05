Netflix Content Analysis Dashboard
📌 Problem Statement

Netflix's content library spans thousands of titles across genres, ratings, and countries, making it difficult for stakeholders to quickly understand content trends. This project analyzes Netflix's movie and TV show catalog to uncover content growth trends over time, genre and rating distribution, and regional availability — with a drill-down view for exploring individual titles.

🛠️ Tools & Technologies
MySQL — data cleaning and pivoting (reshaping multi-value fields like genres/countries, aggregating counts)
Power BI — data modeling, DAX measures, and interactive dashboard design
Excel — supplementary data checks and formatting
📊 Dataset

Public Netflix titles dataset (movies and TV shows metadata: title, genre, rating, release year, country, cast, director, date added).

📈 Dashboard Overview
Page 1: Summary Dashboard
KPI Cards — Total TV Shows (2,676) and Total Movies (6,131)
Shows Added by Date — Area chart showing content growth trend from 2013–2021, split by Movie vs. TV Show
Shows by Rating — Bar chart of content classification (TV-MA, TV-14, TV-PG, etc.)
Top 10 Genres — Horizontal bar chart ranking the most common genres
Countries Available — Map visual showing global content distribution
Page 2: Title Detail View
Searchable slicer to select any individual title
Dynamic cards for Release Year and Rating
Synopsis, Genre, Director, and Cast details
Country availability map filtered to the selected title
🔍 Key Insights
Content additions peaked around 2019, suggesting a shift toward original content production over acquired titles.
TV-MA and TV-14 are the dominant ratings, indicating Netflix's catalog skews toward mature/teen audiences.
International Movies and Dramas are the top genres, reflecting a strong global (non-US-centric) content strategy.
🖼️ Preview

<img width="1148" height="690" alt="image" src="https://github.com/user-attachments/assets/18994c11-48ba-4394-a66b-44ae10f4aede" />

<img width="1151" height="693" alt="image" src="https://github.com/user-attachments/assets/0d59c4f4-3ac3-4e57-9074-6b39e83d332a" />



![Summary Dashboard](screenshots/summary-dashboard.png)
![Title Detail View](screenshots/title-detail.png)

📂 Repository Contents
├── netflix_dashboard.pbix       # Power BI dashboard file
├── screenshots/                 # Dashboard preview images
└── README.md

🚀 What I'd Do Next
Add year-over-year growth % as a calculated DAX measure
Build a content recommendation logic based on genre/rating clusters
Automate data refresh from a live source instead of a static CSV
