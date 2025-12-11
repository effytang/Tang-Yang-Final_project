# Analysis of Popular Film Data via TMDb API

**Authors:** Effy Tang & Weiqi Yang  
**Course:** SURVMETH 727
**Date:** December 2025

---

## Project Overview

Analysis of 164 popular films from The Movie Database examining relationships between budget, genre, release year, and commercial success.

## Files

- `727 final project.Rmd` - R Markdown source code
- `727 final project.pdf` - Final report

## How to Run

### To replicate with your own API key:
1. Get a TMDb API key: https://www.themoviedb.org/settings/api
2. Create `.Renviron` file with: `TMDB_KEY=your_api_key_here`
3. Restart R and open `FinalProject_Improved.Rmd` in RStudio
4. Click **Knit**

## Key Findings

- Budget-Revenue correlation: r ≈ 0.60 (moderate positive)
- Crime, Fantasy, and Drama genres receive highest ratings
- Dataset dominated by 2024-2025 releases
