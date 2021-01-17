# About the project
The project was built by me as one of the side projects during my internship at IIT Kanpur, May 2019.

The project is a recommender system which is made using Colaborate filtering.
Colaborate filtering is a complex deep learning techniques to derive exbeddings corresponding to any object with the help of information that we have for that object.

Here in this project we have considered 2 main entities
 1) Movie
 2) Viewer
 
Now we have created Matrix which is the score a viewer gives to a particular movie. Hence we have initially taken several movies and several viewrs and we have created
a score matrix as the data to train the model for supervised learning.

We then train our model using colaborate filtering and we are able to get embedding corresponding to each movie and each viewer.

Hence we then save these embedddings to understand about the viewer and about the movie ,so that we can give recommendations to them in future.
