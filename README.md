# 🎧 Music Listening Analytics

> Exploring patterns in my current everyday listening with Python, Pandas and Matplotlib.

## About the Project

Music is something I interact with every day, so I decided to turn my current listening habits into a small personal data analytics project.

My music taste is broad, ranging from R&B — one of my favorite genres — to electronic, experimental music, pop, rock, Celtic music and many other styles.

Recently, I have been especially interested in female artists and vocalists, so I used this particular listening phase as the starting point for the dataset.

The goal is not to define my entire music taste from 19 songs. Instead, this project treats the dataset as a **snapshot of one listening period** and explores the patterns inside it.

---

## 📊 Dataset

The current dataset contains **19 songs** from my everyday rotation.

For each track, I record information including:

- artist
- song
- whether it is a recent discovery
- whether I consider it a favorite
- personal notes
- genre
- subgenre
- release year
- artist origin

The dataset is stored in:

`data/listening_history.csv`

---

## 🔎 Questions Explored

Using Python, I explored questions such as:

- Which genres appear most frequently in my current rotation?
- How recent is the music I am listening to?
- Which countries are most represented?
- Which artists appear multiple times?
- Which songs are long-term favorites?
- Which tracks are recent discoveries?

---

## 🎵 Genre Analysis

Electronic music is the largest genre category in this dataset:

| Genre | Songs |
|---|---:|
| Electronic | 8 |
| Pop | 5 |
| R&B | 4 |
| Hip-Hop | 1 |
| Rock | 1 |

Electronic music represents approximately **42% of the current dataset**.

This was interesting because R&B is one of my favorite genres overall, while this particular listening period shows a stronger concentration of electronic and experimental sounds.

---

## 📅 Release Year Analysis

The dataset includes music from several different periods, ranging from **1979 to 2025**.

**10 of the 19 songs were released from 2020 onward**, representing **52.6%** of the dataset.

This suggests that my current rotation leans slightly toward recent releases while still including older music from different decades.

---

## 🌍 Artist Origin Analysis

The USA and UK are the most represented artist origins in this dataset.

The rotation also includes artists associated with:

- Finland
- Denmark
- Australia
- Sweden
- Canada

This analysis is based on songs rather than unique artists, meaning artists represented by multiple tracks have a larger influence on the totals.

---

## 💿 A Few Personal Highlights

Some tracks in the dataset have been favorites for a long time, while others are recent discoveries.

**Kelela — "linknb"** has been one of my favorites since its release, while **Fleetwood Mac — "Sisters of the Moon"** is another long-term favorite.

More recent discoveries include **Eartheater — "Vasp in the Fig"** and **Fine — "A Star"**, with "Vasp in the Fig" currently being one of the tracks I return to repeatedly.

These personal variables make the dataset more than a collection of music metadata: they allow me to eventually compare long-term favorites with newer listening patterns.

---

## 🛠️ Tools & Skills

This project uses:

- Python
- Pandas
- Matplotlib
- Jupyter Notebook / Google Colab
- CSV data
- GitHub
- Data cleaning
- Filtering
- Categorical analysis
- Percentage calculations
- Data visualization
- Data interpretation

---

## 📁 Repository Structure

```text
music-listening-analytics/
│
├── data/
│   └── listening_history.csv
│
├── notebooks/
│   └── music_analysis.ipynb
│
└── README.md
