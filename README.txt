# MovieLens ml-latest-small Dataset

This repository contains the **ml-latest-small dataset** from [MovieLens](http://movielens.org), a movie recommendation service. It provides 5-star ratings and user-generated tags for movies, useful for recommender system experiments, data analysis, and machine learning projects.

---

## 📊 Dataset Overview

- **Ratings**: 100,836 ratings from 610 users on 9,742 movies  
- **Tags**: 3,683 tag applications by 610 users  
- **Time Range**: March 29, 1996 – September 24, 2018  
- **Users**: Randomly selected; each rated at least 20 movies  
- **Files**:
  - `movies.csv` – Movie IDs, titles, genres  
  - `ratings.csv` – User ratings with timestamps  
  - `tags.csv` – User-generated tags with timestamps  
  - `links.csv` – Links to external movie databases (IMDb, TMDb)

> All data is anonymized; no demographic information is included.

---

## 🔧 Data Format

- CSV files, UTF-8 encoded, comma-separated values  
- Headers included; strings with commas are quoted  
- Ratings are on a 0.5–5 star scale  
- Tags are user-provided keywords or short phrases  

---

## 📌 Usage

- **Research and Learning**: Suitable for building recommender systems, collaborative filtering experiments, and ML pipelines.  
- **Non-commercial Use Only**: Must follow the [usage license](#license).  
- **Cross-validation**: Precomputed folds are not included; modern ML toolkits provide built-in methods.

---

## ⚖️ License & Citation

**Usage License**:

- May be used for research and educational purposes only  
- Must acknowledge MovieLens dataset in publications  
- Redistribution allowed under the same conditions  
- Commercial use requires permission from GroupLens

**Citation**:

> F. Maxwell Harper and Joseph A. Konstan. 2015. *The MovieLens Datasets: History and Context.* ACM Transactions on Interactive Intelligent Systems (TiiS) 5, 4: 19:1–19:19. [https://doi.org/10.1145/2827872](https://doi.org/10.1145/2827872)

---

## 🔗 Additional Information

- Visit [MovieLens](http://movielens.org) to explore the live recommender system  
- GroupLens Research: [http://grouplens.org](http://grouplens.org)

---

## ⚙️ Recommended Tools

- Python: `pandas`, `numpy`, `scikit-learn`  
- Recommender system libraries: `Surprise`, `LensKit`  
- Visualization: `matplotlib`, `seaborn`
