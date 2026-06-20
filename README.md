# Interactive Content Insights — Netflix Dataset

A Python data analytics project that explores **9,837+ movie records** to identify genre trends, popularity patterns, vote-average insights, and release-year behaviour. The project demonstrates an end-to-end exploratory data analysis workflow using **Python, Pandas, Matplotlib, and Seaborn**.

This repository is designed as a clean GitHub portfolio project for showcasing data cleaning, classification, exploratory analysis, visualisation, and business-focused insight generation.

## Repository Description

Interactive Python data analytics project analysing 9,000+ movie records through data cleaning, genre classification, popularity analysis, vote-average insights, release-year trends, and visual storytelling.

## Business Context

Streaming platforms use data to understand content performance, audience behaviour, and catalogue trends. This project uses a movie dataset to answer practical business questions such as:

1. What is the most frequent movie genre?
2. Which movie has the highest vote average?
3. Which movie has the highest popularity, and what is its genre?
4. Which movie has the lowest popularity, and what is its genre?
5. Which year has the highest number of released movies?

## Key Findings

- **Most frequent genre:** Drama (3,733 movies)
- **Highest popularity:** Spider-Man: No Way Home — Genre: Action, Adventure, Science Fiction — Popularity: 5083.954
- **Lowest popularity after cleaning invalid rows:** The United States vs. Billie Holiday — Genre: Music, Drama, History — Popularity: 13.354
- **Highest vote average:** Kung Fu Master Huo Yuanjia — Vote Average: 10.0 — Vote Count: 1
- **Year with most movies:** 2021 (714 movies)

## Project Structure

```text
netflix-content-insights-python/
│
├── README.md
├── netflix_analysis.ipynb
├── requirements.txt
├── data/
│   ├── netflix_titles.csv
│   └── README.md
├── images/
│   ├── charts/
│   │   ├── top_10_genres.png
│   │   ├── top_release_years.png
│   │   ├── top_10_popularity.png
│   │   └── vote_average_distribution.png
│   └── screenshots/
│       └── .gitkeep
├── docs/
│   └── Netflix_data_analysis_brief.pdf
├── .gitignore
└── LICENSE
```

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Skills Demonstrated

- Data cleaning
- Exploratory data analysis
- Data visualisation
- Feature extraction
- Genre classification
- Trend analysis
- Business insight generation
- Reusable Python workflow development
- Communicating findings for non-technical audiences

## How to Run This Project

1. Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/netflix-content-insights-python.git
cd netflix-content-insights-python
```

2. Create and activate a virtual environment:

```bash
python -m venv .venv
```

On Mac/Linux:

```bash
source .venv/bin/activate
```

On Windows:

```bash
.venv\Scripts\activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Open the notebook:

```bash
jupyter notebook netflix_analysis.ipynb
```

5. Run the notebook cells from top to bottom.

## CV Project Description

**Interactive Content Insights — Netflix Dataset**  
Python | Pandas | Matplotlib | Seaborn | Jupyter Notebook

- Built an end-to-end Python analytics project analysing 9,000+ movie records to identify genre trends, popularity patterns, vote-average insights, and release-year behaviour.
- Cleaned and structured raw movie data by handling missing values, inconsistent formats, genre classification, and reusable data-preparation steps.
- Created exploratory visualisations to communicate findings clearly for technical and non-technical audiences.
- Produced business-ready insights on most frequent genres, highest popularity titles, vote-average leaders, and peak release years.

## License

This project is licensed under the MIT License.
