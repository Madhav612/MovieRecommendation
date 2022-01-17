# MovieRecommendation

This is part of the online course available on the Udemy. https://www.udemy.com/course/deeplearning/

Here I have learned how to build a recommender system using Boltzmann Machine and AutoEncoders.
First we used Boltzmann Machine, We have achieved the loss of around 0.25 in Boltzmann Machine. Here, we considered the rating of 1,2 as 0 which is disliking the movie and 3,4,5 as 1 which is liking the movie. This was quite easy to predict, because we were doing binary prediction guessing whether user would like a new movie or not and we were correct 3 times out of four. 

Second we implemented recommender system using AutoEncoders where we actually tried to predict the rating out of 1 to 5 and compared it with actual ratings customer gave and we were only 1 rating point off than actual rating. To be more accurate, our training loss was 0.91 and test loss was 0.96. 
