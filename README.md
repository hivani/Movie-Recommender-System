# Movie-Recommender-System
Recommender System is a framework that looks to foresee or filter as indicated by the user's choices. Recommender systems are used in an assortment of regions including films, music, news, books, research articles, search questions, social labels, and items overall.Recommender systems produce a rundown of suggestions inany of the two different ways -Collaborative filtering: Collaborative filtering approaches assemble a model from the user's previous conduct (for example things bought or looked by the user) as well as comparative choices made by different users. This model is then used to foresee things (or appraisals for things) that users might have an interest in.Content-based filtering: Content-based filtering approaches involves a progression of discrete attributes of a thing to suggest extra things with comparable properties. Content-based filtering strategies are completely founded on a depiction of the thing and a profile of the user's choices. It suggests items in view of the user's previous decisions made.We will foster a fundamental recommendation system utilizing Python and Pandas.We will concentrate on providing a basic recommendation system by putting forward items that are mostly similar to the particular item, so in our case it’s movies. It suggests what movies are most similar to the user's movie choice

# Content based algorithm

•Content based system suggests items that a user has enjoyed or purposed before. Assuming if any 
items are loved, comparable items will be suggested. It depends on properties of every items to 
measure the comparability. The point of content based is that we need to know the content of both 
the user and items. Recommendations depend on the content of items rather than other user's 
perspective.

•The film recommender system is valuable in recommending or to predict and filter preferences 
as indicated by the user's decision.

•Recommender systems are utilized in assortment of regions including movies, music, news, 
books, article, and social labels.

•It assists the users with exploring through movies that they are searching for which helps the user 
to save time.

•First and foremost, we get the information of films containing attributes title, movie id and genre 
and rating and afterwards we combine these two datasets which make a rating information outline 
with normal rating. With the accomplishment of registration and login module, we have finished 
the user side and administrator side entry page, The users are shown various movies with respective 
movie rating, title, cast, crew and so forth, which finishes fundamental review module resulting 
into view part from user side.

# Algorithm 
```sh
Step 1. Construct a data frame of the genre dataset with movie ID where the rows and genres as 
columns separated by pipeline character

Step 2. Make a list of all the genres that are available in the dataset. 

Step 3. Iterate through the previously made genre data frame. If a genre is present in a movie, the 
value of I is assigned to the genre matrix 

Step 4. Then Read the ratings sheet and construct a ratings matrix which assigns I for movies 
which has rating more than 3 and -1 for movies which has ratings less than or equal to 3

Step 5. Calculate the dot product of the two matrices-genre matrix and ratings matrix. This is the 
result matrix

Step 6. Convert the result matrix to a binary format. Then f or a negative dot product value, assign 
0, else assign a value of 1.

Step 7. Calculate the Euclidian distance between the current user and other users. 

Step 8. Reteam the rows which have the minimum distance. These are the recommended movies 
for the current user

```sh
