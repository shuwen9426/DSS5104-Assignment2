# DSS5104-Assignment2

# Two-Tower Recommendation Models on MovieLens and Last.fm
This repository contains the code for assignment 2 on two-tower recommendation models implemented with PyTorch.The project includes two experiments:

1. MovieLens
   - A two-tower recommendation model with side features
   - User features: gender, age, occupation
   - Item features: movie genres

2. Last.fm
   - A two-tower recommendation model for implicit feedback
   - Built on user-artist interaction data without explicit ratings
---

## Repository Structure

.
├── 5104_Assignment2_tow-tower model.ipynb     
├── ratings.csv                    # MovieLens ratings data
├── users.csv                      # MovieLens user features
├── movies.csv                     # MovieLens item features
├── user_artists.dat               # Last.fm interaction data
├── requirements.txt
└── README.md
