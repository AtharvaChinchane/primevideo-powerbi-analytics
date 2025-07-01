# 📊 Prime Video Shows Dashboard (Power BI)

This Power BI dashboard presents detailed insights into the content available on **Amazon Prime Video**, including movies and TV shows, categorized by genre, country, ratings, release year, and more.

## 📁 Dataset Overview

- **Source**: Amazon Prime Video dataset (CSV/Excel format)
- **Total Titles**: 9,655
- **Date Range**: 1920 – 2021
- **Fields Used**:
  - `show_id`
  - `type` (Movie or TV Show)
  - `release_year`
  - `country`
  - `rating`
  - `genre`
  - `director`

## 📈 Visuals in the Dashboard

### 1. KPIs (Top Row)
- **Total Titles**: Number of total movies and TV shows
- **Total Ratings**: Unique ratings like PG, R, etc.
- **Total Genres**: Total unique genres in the dataset
- **Total Directors**: Unique directors
- **Start & End Year**: Range of release years

### 2. Ratings by Total Shows
- A horizontal bar chart showing the number of titles per content rating (e.g., 13+, 18+, PG-13).

### 3. Genres by Total Shows
- Bar chart indicating the top genres based on total count of shows.

### 4. Total Shows by Country
- A filled map indicating the number of titles by country of origin.

### 5. Movies and TV Shows (Pie Chart)
- A donut chart showing the percentage and count of Movies vs TV Shows.

### 6. Total Shows by Release Year (Line & Area Chart)
- A trend chart showing how many titles were released each year, split by type.

## 🎨 Design & Theme
- Dark mode layout for better contrast and readability
- Custom color palette:
  - **Movies**: Blue
  - **TV Shows**: Green
- Background images and logos embedded for brand recognition

## 🛠 How to Use or Extend

1. Open the `.pbix` file in Power BI Desktop.
2. Use the filters on the right panel to:
   - Filter by release year
   - Toggle content types (Movie, TV Show)
3. You can edit visuals or create new ones based on:
   - Country
   - Director
   - Genre
   - Ratings

## ✅ Future Improvements
- Add drill-through pages for individual countries or genres
- Include average IMDb score if available
- Create bookmarks for pre-filtered views


---

📧 For questions or suggestions, feel free to raise an issue or contribute.
