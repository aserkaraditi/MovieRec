# MovieRec

This project incl. a content based recom system which gives movie suggestion based on the user entered movie name. 
It uses Tfidfvectorization to transform text into numbers and uses cosine similarity to create a similarity score. 

I selected a few columns like the genre, cast , director etc as the factors that will determine similar movies, combined them in dataset and transformed them into vectors using Tfidfvectorize 
and then uses those to put in the cosine_similarity function to find a smilarity score.

When a user enters a movie name, it finds the index of that movie in the dataset and 
Based in the index of the movie given by user , it compares its similarityscore to the others and produces similar movies.

Here, this code generates top 5 similar movies which can be altered to generate more.
