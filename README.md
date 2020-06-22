# Music-Recommendation-System
A music recommendation system is built based on previous music play amount of users. There are three kinds of methods using in this project:

- Recommendation System Ⅰ: based on the top list of music
- Recommendation System Ⅱ: based on the similarity of music
- Recommendation System Ⅲ: based on Singular Value Decomposition


## Task Flow
<div align="center">
<img src="https://github.com/JimengShi/Music-Recommendation-System/blob/master/images/Flow.png" alt="Workflow" >
</div>


## Recommendation System Ⅰ: based on the top list of music
- It's useful for new users, which can solve the "Cold Starting Problem".
- I created a function `create_popularity_recommendation(train_data_set, user_id, item_id)`
  - train_data_set: the data set you want to analyze to do a recommendation system
  - user_id: user_id
  - item_id: the index you want to recommend based on, e.g., song title, release name, singer name
- For showing the recommendation music clearly, we use `score` to represent the results and use `Rank` to show priority.
- You can find the result as below:

<div align="center">
<img src="https://github.com/JimengShi/Music-Recommendation-System/blob/master/images/Recommendation%201.png" alt="Workflow" >
</div>


## Recommendation System Ⅱ: based on the similarity of music

- You can find the result as below:

<div align="center">
<img src="https://github.com/JimengShi/Music-Recommendation-System/blob/master/images/Recommendation%202.png" alt="R2" >
</div>


## Recommendation System Ⅲ: based on Singular Value Decomposition

- You can find the result as below:

<div align="center">
<img src="https://github.com/JimengShi/Music-Recommendation-System/blob/master/images/Recommendation%203.png" height="80%" alt="Workflow" >
</div>
