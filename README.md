# Group 5 - Gamers: Analyzing Critic vs Player Game Reviews

A data-driven exploration of how critic scores compare to player sentiment on Steam games, using visualization and machine learning models.

## Team Members
- Alvin Lee
- Andy Liu
- Thi Ngoc Duyen Lam
- Ronald Celino

## Problem Overview

Critic reviews and player opinions often don't align in the gaming world. This project investigates:

- Whether critic scores (Metacritic) align with player sentiment (Steam reviews)
- Potential biases in critics or player communities
- Factors influencing game success (genre, tags, popularity)

We aim to build predictive models that estimate player reception based on game features.


## Dataset

- Source: Kaggle Steam Games Dataset (March 2025)
- File: `games_march2025_cleaned.csv`
- Size: ~90,000+ games, 40+ features

### Key Features:
- `metacritic_score` (critic rating)
- `pct_pos_total` (player sentiment)
- `genres`, `tags`
- `peak_ccu` (popularity)
- `price`, `release_date`


# Important
Dataset file too large to be included within the repo
Instead, the dataset can be downloaded from:
https://www.kaggle.com/datasets/artermiloff/steam-games-dataset

Then upload it to your Google Drive before running notebooks.


## How to Run the Project (Google Colab)

1. Download the dataset from Kaggle
2. Upload it to your Google Drive

3. Open any notebook in Google Colab

4. Mount your Google Drive:
```python
from google.colab import drive
drive.mount('/content/drive')  

5. update the dataset filepath if need be ( file_path = "/content/drive/MyDrive/<your-folder>/games_march2025_full.csv" )
6. Run all cells by clicking the 'Run all' button in the top left of the Colab UI





