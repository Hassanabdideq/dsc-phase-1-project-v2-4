# Overview

This project focuses on Microsoft's ambition to establish a new movie studio dedicated to producing original video content, aligning with other industry giants. The project encompasses the entire data science pipeline, from data collection and **cleansing** to in-depth analysis and visualization. In this README, you will discover comprehensive details about the project's background, data sources, analytical insights, and conclusive findings.

# Business Understanding

In this section we dive into motivation behind Microsoft's ambition to establish a movie studio. Creating original video's has been one of the most ways tech giant generating lots of revenue. Besides creating video content for fun the also ways to promote brand of big tech companies.

The primary objective is to understand movies that are doing great in box office so that Microsoft uses finding from this analysis to make decision to create original video content that will also do great in box office.

The role of this project is explore the available data to make valuable insight. This insights will guide Microsoft in making decision to guide Microsoft on creating videos content and audience it will target to gain a great success in the box office and also compete with other video contents

# Main objective

- To understand factor afecting performancy of movies in box office
# Specif objective 
 - To know most profitable movies genres
 - To know most rated movie genres
 - To know most voted movie genres
  

# Data understanding

For the data in this section i will be using sqlite database from **im.db** which containts tables like movie_ratings, movie_basic table which are promising in the analysis since they have movie titile, genres, runtime, average ratings and number of votes the movies have. On the other hand the data lacks revenue generated from the movies so we will compine the above database with **bom.movies_gross.csv.gz** which provides revenue generated which are gross income form the movie both foreign and domestic 



# Recommendation and Conclusions

## Conclusions

- Building upon our analysis, it's evident that there exists a positive correlation between profit and the number of votes (0.61). Additionally, we observe another noteworthy correlation between runtime and profit (0.2). These statistical relationships shed light on the factors influencing a movie's financial success. As we delve deeper into our findings, we uncover more insights into the film industry's dynamics

- The most rated and profitable genres are Adventure, Drama, Sport, and Family.

- The most profitable genres in our analysis include Adventure, Drama, Sport, Family, Documentary, Sci-Fi, Fantasy, Comedy, Mystery, and Action. These genres have demonstrated strong financial performance in the film industry.
  
- The most rated genres in box office are Adventure,Action Sport, Drama Western, Adventure Drama Sci-Fi, Crime Documentary Fantasy, Biography Documentary Thriller, Comedy Crime Documentary, Documentary Family, Animation Biography Crime, 

- In the category of "Top Voted Genres," several genres have garnered significant attention and acclaim. These genres include Drama, Western, Adventure Drama Sci-Fi, Adventure Mystery Sci-Fi, Comedy Mystery, Action, Adventure, Sci-Fi, Mystery Sci-Fi Thriller, Action Adventure Mystery, Drama Sci-Fi Thriller, Action Mystery Sci-Fi, and Mystery Thriller. These genres have received notable recognition and appreciation, reflecting their popularity among viewers and critics alike. Their diverse themes and storytelling styles have contributed to their appeal and made them stand out as top choices in the world of cinema.

## Recommendations

- When selecting a movie to produce, genre, average rating, number of votes, and profitability should be the primary factors to consider.

- Focus on high-demand genres with strong profitability: Genres like Action, Adventure, Sci-Fi, Adventure, Animation, Comedy, and Action, Adventure, Fantasy have demonstrated significant profits. Investing in these genres can offer potential returns on investment due to their popularity and financial success.

- Consider genres with high ratings and reasonable budget requirements: Genres like Drama, Documentary, Adventure, Drama, Sci-Fi receive high ratings and have manageable budgets. These genres strike a balance between critical acclaim and financial viability, making them promising investment options.

- Explore opportunities in popular genres with high profitability potential: Genres like Drama, Comedy, and Adventure, Animation, Comedy are popular and typically come with moderate production costs. Investing in these genres can tap into widespread audience appeal while effectively managing production expenses, potentially leading to profitability.

