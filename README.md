# DM_Project: Anime Recommendation System

## Dataset and Content

In this project, we are working on a recommendation system to answer the question: "Which anime should you watch next?" using an anime dataset containing two CSV files:

- **anime.csv**: Contains metadata about the anime (e.g., genre, type, rating, number of episodes).
- **rating.csv**: Contains ratings from users for different anime (user-item interactions).

We used three notebooks for this project:

- **eda.ipynb**: For exploring and analyzing the data.
- **rec_sys_content.ipynb**: Used to build a basic content-based recommendation system.
- **rec_sys_collaborative.ipynb**: Used to build multiple collaborative filtering recommendation systems based on various methods.


## Run the code
As we preferred to use Conda, we utilized it to create our environment. We did not include the environment.yml file due to compatibility issues across different platforms (e.g., some have NVIDIA GPUs, while others do not). Instead, we provided the commands to create a new Conda environment and installed all necessary packages listed in requirements.txt. Below are the commands, in order:

```
conda create --name dm python=3.13.0
conda activate dm
pip install -r requirements.txt
```

The installation of Jupyter Notebook or Jupyter Notebook extensions in VS Code is necessary to rerun the cells.