# Netflix-power-bi-dashboard
Power Bi dashboard analyzing Netflix dataset from kaggle 

# 📺 Netflix Movies and TV Shows Dashboard (Power BI)

This repository contains an interactive Power BI dashboard built using the [Netflix Movies and TV Shows dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows). The dataset provides information about the content available on Netflix up to 2021, including details such as title, type, country, release year, duration, rating, and more.

---

## 📁 Dataset Overview

- Source: [Kaggle - Netflix Titles Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- Author: Shivam Bansal
- Total records: 8,802 titles
- Types of content: Only two — `Movie` and `TV Show`
- Time period: Covers titles added to Netflix until 2021

---

## 📊 Dashboard Features

The Power BI dashboard includes visualizations and KPIs such as:

- Total Titles: 8,802
- Total Ratings: 18 unique rating types (like TV-MA, PG, R, etc.)
- Total Directors: 4,526 unique director entries
- Type Breakdown:
  - TV Shows: 6,130 (approx. 69.6%)
  - Movies: 2,680 (approx. 30.4%)
- Top countries by number of titles: United States, India, United Kingdom, Japan, South Korea
- Most frequent tags from the `listed_in` column: 
  - Dramas, International Movies
  - Documentaries
  - Stand-Up Comedy
  - Kids' TV
  - Children & Family Movies
- Titles by release year: Noticeable increase in content after 2010
- Map visualization for country-wise content distribution

---

## 📦 Columns in the Dataset

The dataset includes the following columns:

- `show_id`: Unique ID for each title  
- `type`: Type of the content (`Movie` or `TV Show`)  
- `title`: Name of the movie or TV show  
- `director`: Director of the content (may be null)  
- `cast`: Leading actors in the title (may be null)  
- `country`: Country of origin (may be multiple or null)  
- `date_added`: Date the content was added to Netflix  
- `release_year`: Year the content was originally released  
- `rating`: Age classification (e.g., TV-MA, PG, etc.)  
- `duration`: Length of the content (in minutes or number of seasons)  
- `listed_in`: Category or genre tags (e.g., "Dramas, International Movies")  
- `description`: Short summary of the content  

---

## 🛠 Tools Used

- Power BI Desktop
- Power Query (for data cleaning)
- Bing Maps (for geographical visuals)
- CSV file (as downloaded from Kaggle)

---

## 🧠 Key Insights

- TV Shows are more prevalent than Movies on Netflix.
- The United States is the top contributor of Netflix content.
- Content volume saw a significant rise after 2010.
- Categories like "Dramas, International Movies", "Documentaries", and "Stand-Up Comedy" appear frequently.

---

---

## 📂 Repository Structure

📁 Netflix-PowerBI-Dashboard
│
├── Netflix_Dashboard.pbix # Power BI dashboard file
├── netflix_titles.csv # Dataset used
├── dashboard_screenshot.jpg # Dashboard preview image
└── README.md # Documentation

---

## 🙌 Credits

- Dashboard created by: [Richa Kumari](https://www.linkedin.com/in/richa-kumari-81548331a)

---

## 📄 License

This project is intended for educational and portfolio purposes only.




