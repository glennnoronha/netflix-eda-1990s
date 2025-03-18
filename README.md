# netflix-eda-1990s
"Exploratory Data Analysis (EDA) on Netflix movies from the 1990s. Identifies the most common movie duration and counts short action movies under 90 minutes.

# Netflix Movies EDA (1990s)

## Project Overview
This project performs **Exploratory Data Analysis (EDA)** on Netflix movies from the 1990s. It focuses on:
- Identifying the most frequent movie duration in the decade.
- Counting the number of short action movies (less than 90 minutes long).

## Dataset
The dataset used is **netflix_data.csv**, which contains information about movies, including:
- `show_id` - Unique identifier
- `type` - Whether it's a Movie or TV Show
- `title` - Movie title
- `director` - Director's name
- `cast` - Main cast
- `country` - Country of production
- `release_year` - Year the movie was released
- `duration` - Length of the movie in minutes
- `genre` - Genre of the movie
- `description` - Short description of the movie

## Analysis Performed
1. **Filtering**: Extracting movies released between 1990 and 1999.
2. **Cleaning**: Ensuring durations are in numerical format.
3. **Finding Most Common Duration**: Identifying the most frequent duration for movies in this decade.
4. **Counting Short Action Movies**: Filtering and counting action movies under 90 minutes.

## Results
- **Most Frequent Duration**: 108 minutes
- **Short Action Movies Count**: 6

## How to Run the Project
### Requirements
Ensure you have the following installed:
- Python (>=3.7)
- Pandas
- Matplotlib
- Jupyter Notebook (if running the notebook version)

### Steps
1. Clone the repository or extract the files.
2. Install dependencies:
   ```sh
   pip install pandas matplotlib jupyter
   ```
3. Open `notebook.ipynb` in Jupyter Notebook and run the cells.
4. Check the printed outputs for insights.

## File Structure
```
workspace/
│── notebook.ipynb        # Jupyter Notebook with the analysis
│── netflix_data.csv      # Dataset used
│── redpopcorn.jpg        # Project image
│── README.md             # This documentation
```

## Notes
- The analysis is basic but can be extended with more insights like genre distributions, rating analysis, or visualizations.
- You can experiment further by modifying filtering criteria or adding new plots.

## License
This project is for educational purposes and follows an open-source license.


