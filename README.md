# Movie Recommendation System

## Team Members
- ruby2514

## Dataset
CiaoDVD - A real-world movie rating dataset containing:
- 72,665 ratings
- 17,615 unique users
- 16,121 unique movies
- Ratings on a 1-5 scale
- 99.97% sparsity

## Installation
```bash
pip install pandas numpy matplotlib seaborn scikit-surprise
```

## How to Run
1. Clone this repository
2. Download movie-ratings.txt from https://guoguibing.github.io/librec/datasets.html
3. Place movie-ratings.txt in the root folder
4. Run 01_eda.ipynb first
5. Then run 02_models.ipynb

## Results Summary
| Model | RMSE | MAE |
|-------|------|-----|
| Global Average | 0.9432 | 0.7329 |
| User-Based CF | 1.0708 | 0.8127 |

Global Average outperformed User-Based CF due to extreme data sparsity.
