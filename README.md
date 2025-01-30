# Moneyball in *Football Manager 2023*
### This project aims to showcase practice of data science techniques to recruit players in Sports Interactive's football simulation game, *Football Manager*

*Football Manager* is a series of football management simulation video games developed by Sports Interactive (SI) that many football nerds, including myself, may be familiar with. It is the most widely played football management simulation game in the world, amassing over 7 million players in its latest installment, *Football Manager 2024*. To many, it is a game played almost religiously where strong one-sided relationships are able to be made between the player and their Colombian newgen wonderkid who leads them to promotion. Jokes aside, it is also a tool used by top teams to scout players. Even prominent Premier League side Everton F.C. signed a deal with the developer SI in 2008 to allow them to use SI's database to scout players.

Due to its realism and prominence in the football industry, I wanted to use a data-driven approach to recruitment in a game save I started with FC Girondins de Bordeaux. I would use player data to find lower reputation players that could replicate the output of world class players in the match engine. 

In this project, I used reduced the data using principal component analysis (PCA) followed by a K-means clustering to create clusters of similar players. Then, I would take an outstanding player who contains a profile I would like to recruit for my Bordeaux squad and find the most similar players that could be had for a budget price. 

For example, if I wanted to find a towering centerback who is comfortable on the ball such as Virgil van Dijk, I would use his PCA output and find the centerbacks closest to his metrics, sorting by Euclidean distance. In this approach that most would not make the most use of, I found it an interesting tool to find players who are not always found by the scouts.
