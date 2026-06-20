# GitHub Upload Steps for netflix-content-insights-python

## Option 1: Upload through GitHub website

1. Go to GitHub and sign in.
2. Click the `+` icon in the top-right corner.
3. Click `New repository`.
4. Repository name: `netflix-content-insights-python`
5. Description: `Interactive Python data analytics project analysing 9,000+ movie records through data cleaning, genre classification, popularity analysis, vote-average insights, release-year trends, and visual storytelling.`
6. Select `Public`.
7. Do not tick `Add a README file` because this ZIP already includes one.
8. Do not add `.gitignore` or license on GitHub because this ZIP already includes both.
9. Click `Create repository`.
10. Click `uploading an existing file`.
11. Open the ZIP on your computer and drag all files/folders inside the project folder into GitHub.
12. Click `Commit changes`.

## Option 2: Upload using Git commands

Open Terminal or Git Bash in the project folder and run:

```bash
git init
git add .
git commit -m "Initial commit: Netflix content insights project"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/netflix-content-insights-python.git
git push -u origin main
```

## After Uploading

1. Open your GitHub repository.
2. Check that the README displays properly.
3. Open `netflix_analysis.ipynb` and confirm the notebook loads.
4. Check that chart images appear inside the README.
5. Copy the repository URL and add it to your CV.

## CV Link Format

Use this format in your CV:

```text
Interactive Content Insights — Netflix Dataset
GitHub: https://github.com/YOUR-USERNAME/netflix-content-insights-python
Python | Pandas | Matplotlib | Seaborn | Jupyter Notebook
```
