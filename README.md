# DM_Project : Anime recommandation system
## Approaches
In this project, we are workin on a recommendation system problem using an anime dataset which has two csv files:
**anime.csv:** Contains metadata about the anime (e.g., genre, type, rating, number of episodes).
**rating.csv:** Contains ratings from users for different anime (user-item interactions).

! data cleaning: 
for the users: keep only the users with plus than 3 rating 

for the anime: keep only the anime with more than 10 ratings 

Insure that the tdata is representative

### 1 Content-based filtering (CBF)

### 2 Collaborative filtering (CF)
These techniques rely on calculating similarities directly between users or items.

#### 2.1 Memory Based Collaborative Filtering
Concept: Recommend items that users with similar tastes have rated highly.
Implementatin : Create a user-item matrix where the rows represent users and the columns represent items (anime in this case), with the ratings as entries. Then, calculate the similarity between users using a distance metric (cosine similarity, Pearson correlation, or Jaccard index).

##### 2.1.1 User-based collaborative filtering (UBCF)

##### 2.1.2 Item-based collaborative filtering (IBCF) 
KNN: https://www.geeksforgeeks.org/recommendation-system-in-python/



















#### 2.2 Model Based Collaborative Filtering

