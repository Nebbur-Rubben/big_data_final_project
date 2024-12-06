# Movie Recommendation System

## Project Overview
This project implements a **movie recommendation system** using the MovieLens dataset. The goal is to analyze user preferences, generate personalized movie recommendations, and evaluate the recommendation model's performance. Big data processing and machine learning techniques are applied throughout the project.

---

## Features

1. **Data Analysis**
   - Preprocessing and cleaning of the MovieLens dataset.
   - Exploratory data analysis to understand user ratings, movie popularity, and trends.

2. **Recommendation System**
   - Implemented collaborative filtering using the **Alternating Least Squares (ALS)** algorithm.
   - Generated personalized recommendations based on user-item interactions.

3. **Performance Evaluation**
   - Evaluated the model using metrics such as RMSE to measure recommendation accuracy.

4. **Result Visualization**
   - Visualized data insights, including rating distributions, most popular movies, and user-specific recommendations.

---

## Data Sources

- **MovieLens Dataset**: Includes user ratings, movie metadata (e.g., titles and genres), and tags.
  - Link to the dataset: [MovieLens Website](https://grouplens.org/datasets/movielens/)

---

## Technologies and Tools

- **Python**: Core programming language used.
- **PySpark**: For large-scale data processing and model implementation.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib/Seaborn**: For data visualization.
- **Jupyter Notebook**: To document and present the workflow.

---

## Installation and Setup

1. Clone this repository:
   ```bash
   git clone [repository-url]
   cd [repository-folder]

2.Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Download and place the MovieLens dataset in the data/ directory.

4. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
   - Open the notebook file `recommendation_system.ipynb` in the browser.
---
- Identified popular movies based on ratings and user preferences.
- Built a recommendation system capable of providing accurate movie suggestions for individual users.
- Achieved satisfactory performance with RMSE evaluation.

---

## Lessons Learned
- Effective data preprocessing significantly impacts model accuracy.
- PySpark is a powerful tool for handling large-scale datasets efficiently.
- Collaborative filtering algorithms like ALS work well for recommendation systems but require proper hyperparameter tuning.

---

## Future Improvements
- Incorporate additional metadata such as tags and genres into the recommendation model.
- Experiment with hybrid recommendation approaches (content-based + collaborative filtering).
- Optimize performance for even larger datasets.

---

## Authors
- **Yuancheng Wang** (yw8063)
- **Zehao Li** (zl5573)
- **Yang Xu** (yx3315)
