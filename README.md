# SpotifyWrapped Project
Spotify Wrapped sucked, so I made my own. I'm a passionate music lover and was very disappointed with the approach of the most recent Wrapped. I always look for deep analytics into my listening history because I like to see how my tastes have evolved. This is more of a personal project, but I hope it clicks with other music lovers who want to create fun insights into their music history! 


## Overview
This project is an in-depth analysis of my Spotify streaming history, focusing on identifying trends, top artists, genres, and other insights for 2024. It also includes genre mapping for my top 100 artists and SQL scripts to process and query the data effectively.
I was very disppointed with the approach of the most recent Wrapped, so having my own data at home and being able to 

## Features
1. **Top Artists and Genres**:
   - Analyze top artists and genres by playtime and number of plays.
   - Discover new artists and genres introduced in 2024.

2. **Detailed Queries**:
   - Most played songs, albums, and genres of 2024.
   - Compare listening trends with previous years.

3. **Genre Mapping**:
   - Manual genre assignment for the top 100 artists.
   - SQL integration to query genre-based insights dynamically.

4. **Scripts**:
   - SQL scripts to create, populate, and query the Spotify database.
   - Easy integration for expanding the dataset or running new analyses.

## Repository Structure
```
📂 sql_scripts/
   ├── create_tables.sql         # Script to create the main Spotify data table.
   ├── populate_genre_mapping.sql # Script to create and populate the genre mapping table.
   ├── update_spotify_data.sql   # Script to update the main table with genre data.

📂 data/
   ├── streaming_history.json    # Placeholder for your Spotify streaming history.

README.md                        # Overview of the project.
```

## Prerequisites
- **MySQL Database**: Ensure you have MySQL installed to run the SQL scripts. (Not sure how easily it will transfer to other platforms)
- **Spotify Streaming Data**: Export your Spotify streaming history. You can do this directly from the Spotify website itself.
- **Python (Optional)**: For advanced data processing and transformations.

## Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/SpotifyWrapped.git
   cd SpotifyWrapped
   ```

2. Import the SQL scripts into your MySQL database:
   - Start with `create_tables.sql` to set up the schema.
   - Use `populate_genre_mapping.sql` to populate the genre mapping table.
   - Run `update_spotify_data.sql` to add genres to the main Spotify data table.

3. (Optional) Add your `streaming_history.json` to the `data/` directory.
- **Spotify**: For providing streaming history data.
- **MySQL**: For seamless database management.
- **Python**: For additional data transformations and processing.

Feel free to reach out with suggestions or questions!
