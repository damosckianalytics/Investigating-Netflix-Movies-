# Netflix-Movies-EDA-1990s-Focus

# Overview / Introduction

Netflix began as a DVD rental service in 1997 and has since evolved into one of the most influential media and entertainment platforms worldwide. This project explores Netflix’s movie catalogue, with a specific focus on films released during the 1990s—a decade renowned for its distinctive cinematic styles. The analysis aims to support a production company that specialises in nostalgic themes.

# Objectives

1.	To perform exploratory data analysis (EDA) on Netflix’s movie database.
2.	To identify and examine movies released in the 1990s.
3.	To explore trends in genres and durations during this period.
4.	To provide data-driven recommendations for content creators targeting a retro audience.


# Data Source

-	Dataset: netflix_data.csv
-	Features include: show ID, type, title, director, cast, country, date added, release year, duration, description, and genre.
-	The dataset contains 4,812 entries with complete information and no missing values.

# Tools Used

•	Python
•	Pandas – Data manipulation
•	NumPy – Numerical operations
•	Matplotlib & Seaborn – Data visualisation
•	Jupyter Notebook – Interactive development

# Insights

•	Movies released in the 1990s were filtered from the complete dataset.
•	Action movies were isolated to analyse duration trends.
•	The histogram showed a typical distribution of durations, centred around 100 minutes.
•	A small subset of 1990s action films had runtimes under 90 minutes.
![Untitled](https://github.com/user-attachments/assets/1e94fcca-1a97-4589-a0f6-0964afb7b848)


# Key Findings

•	A total of 7 action movies released in the 1990s had a duration of less than 90 minutes.
•	The majority of movies in this era were around 90–120 minutes in length.
•	The genre distribution for the 1990s indicates a strong presence of action, drama, and horror films.

# Recommendation

For production companies aiming to recreate 1990s-style content, focusing on action movies with compact runtimes (under 90 minutes) could resonate well with viewers seeking nostalgic, fast-paced entertainment. Additionally, targeting prevalent genres like drama and horror may further enhance audience engagement.

# How to Use This Repository

1.	Clone the repository or download the files.
2.	Ensure Python and the required libraries (pandas, numpy, matplotlib, seaborn) are installed.
3.	Open the notebook.ipynb file in Jupyter Notebook or Google Colab.
4.	Run all cells to explore the data and visualisations.
5.	Modify the filters (e.g., genre, year range) to perform your own analysis.
