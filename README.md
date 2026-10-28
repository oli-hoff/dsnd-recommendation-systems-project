# Recommendation System: IBM Community

Recommendation engine for articles on the IBM Watson Studio platform, based on user-article interactions. Final project of the Udacity Data Scientist Nanodegree.

## Methods

- Rank based: most popular articles, also used for new users
- User-user collaborative filtering: articles read by similar users (cosine similarity)
- Content based: TF-IDF on the article titles, LSA (TruncatedSVD) and KMeans clustering
- Matrix factorization: SVD on the user-item matrix to find similar articles

## Files

- `starter/Recommendations_with_IBM.ipynb`: notebook with all code and answers
- `starter/Recommendations_with_IBM.html`: HTML export of the notebook
- `starter/project_tests.py`, `starter/top_*.p`: tests provided by Udacity
- `starter/data/user-item-interactions.csv`: user-article interactions

## Getting Started

Dependencies: Python 3, pandas, numpy, matplotlib, scikit-learn, Jupyter.

```
cd starter
jupyter notebook Recommendations_with_IBM.ipynb
```

## Testing

The tests from `project_tests.py` are called inside the notebook. After "Kernel > Restart Kernel and Run All Cells" every test prints a success message.

## License

[License](LICENSE.txt)
