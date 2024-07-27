# newMovieStudio

## Movie Studio Business Insights

### Project Overview
This project aims to provide actionable insights for a new movie studio seeking to understand the movie industry. The focus is on identifying optimal release timings, successful genres, and the relationship between movie runtime, budget, and box office performance to guide the studio's production decisions.

### Business Problem
The company wants to enter the movie industry by creating original video content but lacks knowledge about the movie-making business. The project aims to explore the type of films currently doing the best at the box office and translate these findings into actionable insights for the new movie studio.

### Data Understanding

#### Data Description
The datasets used for this analysis include:
- **bom.movie_gross.csv.gz**: Box office gross data from Box Office Mojo.
- **rt.movie_info.tsv.gz**: Movie information from Rotten Tomatoes.
- **rt.reviews.tsv.gz**: Movie reviews from Rotten Tomatoes.
- **tmdb.movies.csv.gz**: Movie data from The Movie Database (TMDB).
- **tn.movie_budgets.csv.gz**: Movie budgets from The Numbers.
- **im.db**: Additional movie data from IMDB.

### Data Preparation
The datasets were cleaned and merged as necessary. Steps included:
1. Loading and inspecting the datasets.
2. Handling missing values and correcting data types.
3. Merging datasets on common keys such as movie titles and release dates.

### Data Analysis
The analysis addressed the following key questions:
1. **Best Release Seasons**: Analyzed box office performance by release month to identify optimal seasons.
2. **Successful Genres**: Evaluated the popularity and box office success of different genres.
3. **Runtime and Budget Analysis**: Investigated the impact of movie runtime and production budget on box office performance.

### Results

#### Key Findings
1. **Optimal Release Timing**:
   - Movies released during the summer (June to August) and winter holiday seasons (November to December) tend to perform better in terms of domestic gross.
2. **Genre Performance**:
   - Action, adventure, and family-friendly genres show high popularity and profitability. These genres have broad audience appeal and tend to receive higher box office revenue and better reviews.
3. **Budget and Runtime Optimization**:
   - Movies with moderate budgets (between $30M to $100M) and runtimes of 90 to 120 minutes tend to achieve a good balance between production cost and box office revenue.

#### Visualizations
[Include relevant plots and visualizations here]

### Business Recommendations
1. **Release Timing**: Focus on scheduling major movie releases during the summer and winter holiday seasons to maximize box office returns.
2. **Genre Focus**: Prioritize the production of action, adventure, and family-friendly movies. These genres have a proven track record of success and offer higher potential returns.
3. **Budget and Runtime**: Optimize production budgets to fall within the $30M to $100M range and aim for movie runtimes between 90 to 120 minutes. This strategy balances cost and potential revenue, enhancing profitability.

### Next Steps
1. **Further Genre Analysis**: Conduct a deeper dive into sub-genres to identify niche markets.
2. **Marketing Strategy**: Analyze the impact of marketing spend on movie success.
3. **International Markets**: Explore box office performance trends in international markets.

### Repository Structure
