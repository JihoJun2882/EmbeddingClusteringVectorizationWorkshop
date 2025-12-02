# Lab9 Workshop: Embedding & Clustering Vectorization

## Overview
This project explores the fundamental differences in word embedding techniques by comparing **Predictive Models (Word2Vec)** and **Count-based Models (GloVe)**.

## Team Members
| Name | Student ID |
| :--- | :--- | :--- |
| Jiho Jun | 9080800 |
| Vishnu Sivaraj | 9025320   |

## Dataset Description
We utilized two contrasting corpora to analyze domain adaptation and temporal shifts in word meaning.

### 1. Brown Corpus (Control Group)
* **Description:** The first million-word electronic corpus of English, created in 1961. It contains text from 15 categories (News, Religion, Fiction, etc.).
* **Purpose:** Used as a baseline to represent **historical, formal, and general American English**.
* **Source:** Accessed via `nltk.corpus`.
* **License/Link:** [Brown Corpus Manual (NLTK)](https://www.nltk.org/book/ch02.html)

### 2. Netflix Titles (Experimental Group)
* **Description:** A dataset of movies and TV shows available on Netflix, including metadata such as titles, genres, and descriptions.
* **Purpose:** Used to represent **modern, entertainment-focused, and specific domain English**.
* **Preprocessing:** We combined `title`, `description`, and `listed_in` (genre) columns to create a rich context for training.
* **Source:** `netflix_titles.csv` (Originally from Kaggle).
* **License/Link:** [Netflix Movies and TV Shows (Kaggle)](https://www.kaggle.com/datasets/shivamb/netflix-shows) (CC0: Public Domain)

### How to run
1. Install dependencies
- pip install -r requirements.txt
2. Run the Notebook