# Football Player Similarity Engine

A Python-based football analytics project that identifies statistically similar players using performance metrics, distance-based algorithms, and dimensionality reduction.

## Methodology

* Filtered 1,049 outfield players with at least 900 minutes played and the required advanced statistics.
* Selected nine features covering attacking output, progression, creativity, and defensive contributions.
* Standardized features using `StandardScaler`.
* Compared players using **Euclidean distance** and **cosine similarity**.
* Applied **Principal Component Analysis (PCA)** to visualize player profiles in two dimensions.
* Analyzed feature contributions to understand differences between player pairs.

## Example: Lamine Yamal

Used Lamine Yamal as the reference player to identify similar profiles, compare similarity methods, and visualize nearest neighbors.

## Technology Stack

Python, Pandas, NumPy, Scikit-learn, SciPy, Matplotlib, Jupyter Notebook.

## Project Files

* `playersimilarity.ipynb` — complete analysis and visualizations.
* `cleaned_players.csv` — cleaned player dataset.

## Limitations

Similarity depends on the selected features and does not directly account for tactical roles, team context, or league differences. Similar statistical profiles do not necessarily imply identical playing styles or overall ability.

## Future Improvements

Position-specific models, interactive player search, radar charts, and cross-season comparisons.
