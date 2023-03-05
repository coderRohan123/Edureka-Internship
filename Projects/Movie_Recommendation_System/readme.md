<img align="center" alt="Coding" width="1400" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQY7K7GQSxQNLY09wbsGmG2hcfhwU8MhobQyA&usqp=CAU">
<h1 align="center">Hi 👋,This project is based on movie recommendation System</h1>
<h2>Context</h2>
<p> Over the past two decades, there has been a monumental shift in how people access and consume video content. With the universal access to broadband internet, numerous platforms like YouTube, Netﬂix, and HBO Go emerged and steadily grew to prominence. Although not a household name in itself, OTT is the exact technology that made the streaming revolution possible. OTT stands for “Over The Top” which refers to any video streaming service delivering content to the users over the internet, however, there are subscription charges associated with the usage of such platforms such as PrimeVideo, Netﬂix, HotStart, Zee5, SonyLiv, etc. But choosing your next movie to watch can still be a daunting task, even if you have access to all the platforms. </p>
<h2>Objective:</h2> 
1. Create a popularity-based recommender system at a genre level. The user will input a genre (g), minimum rating threshold (t) for a movie, and no. of recommendations(N) for which it should be recommended top N movies which are most popular within that genre (g) ordered by ratings in descending order where each movie has at least (t) reviews.   

2. Create a content-based recommender system that recommends top N movies based on similar movie(m) genres.
3. Create a collaborative based recommender system which recommends top N movies based on “K” similar users for a target user “u”
<h2>Data Description</h2>
<p>The data consists of 105339 ratings applied over 10329 movies. The average rating and minimum and maximum rating are 0.5 and 5 respectively. There are 668 users who have given their ratings for 149532 movies. 
There are two data ﬁles which are provided: 
Movies.csv 
<h3>● movieId: ID assigned to a movie </h3>
<h3>● title: Title of a movie </h3>
<h3>● genres: pipe-separated list of movie genres. </h3>
Ratings.csv 
<h3>● userId: ID assigned to a user </h3>
<h3>● movieId: ID assigned to a movie </h3>
<h3>● rating: rating by a user to a movie </h3>
<h3>● Timestamp: time at which the rating was provided. </h3>
