# Movie Recommendation System - Two Tower Model

A retrieval-based movie recommender built on the MovieLens-1M dataset. User and movie features are encoded into a shared embedding space by two independent neural towers, trained with an in-batch loss and served at inference time via a FIASS nearest-neighbor index.

## Structure:

```
.
├── recommendation_system.ipynb
├── requirements.txt
└── README.md
```

## Setup
```bash
git clone https://github.com/tataumesh/Recommendation_System.git
cd Recommendation_System
python -m venv venv
source venv/bin/activate  # For Linux
pip install -r requirements.txt
```

## Dataset

Download the dataset

```bash
wget https://files.grouplens.org/datasets/movielens/ml-1m.zip
unzip ml-1m.zip
```
MovieLens-1M Dataset
> F. Maxwell Harper and Joseph A. Konstan. 2015. The MovieLens Datasets: History and Context. ACM Transactions on Interactive Intelligent Systems (TiiS) 5, 4, Article 19 (December 2015), 19 pages. DOI=http://dx.doi.org/10.1145/2827872
