# CSE523-Machine-Learning-KHVM
A Music Recommendation System that uses collaborative filtering and machine learning algorithms like K-nearest neighbors and Singular Value Decomposition (SVD) to recommend songs to user based on their preferences. 


**Introduction**

Music Recommend system is a system that seeks to predict or filter preference according to the user’s different choices.It  learns from the user’s past listening history and recommends them  various songs which they would probably like to hear in the future.Collaborative filtering algorithms which predict (filtering) taste of a user by collecting preferences and tastes from many other users (collaborating) are also implemented. In this first phase of the project, we have build a recommender system using k-nearest neighbors algorithm.Our system also uses RMSE which stands for Root Mean Squared Error. The standard deviation of the errors that exist when making a forecast on a dataset is known as the RMSE. The Root Mean Square Error (RMSE) is a matrix for determining how well a regression line matches the data points.Along with RMSE, we have also applied The singular value decomposition (SVD).SVD is another method for factorising a matrix into singular vectors and singular values. The SVD is commonly used in machine learning as a data reduction tool as well as in the estimation of other matrix operations such as matrix inverse.
Our dataset consists of 2 million records containing user ids, song ids and the number of times a user has listened to a particular song.


**Dataset**

Our dataset is too large to be uploaded over here and hence we have uploaded it to Google drive and provided the link below.

https://drive.google.com/drive/folders/1WtPQZ5Ow2H9EJqgyzd49aWfpLYkbAukp?usp=sharing



**Results**

**1. Fuzzy String Matching**

![fuzzy](https://user-images.githubusercontent.com/65005420/114298627-fe973a00-9ad4-11eb-90db-570ba0fa8ccc.JPG)


**2. Recommendations using the K-nearest Neighbours algorithm**

![MUSIC_output_2](https://user-images.githubusercontent.com/65005420/114298631-0656de80-9ad5-11eb-8d10-0a2b31da89dd.jpeg)


**3. Recommendation using the Singular Value Decomposition algorithm**

![svd_1](https://user-images.githubusercontent.com/65005420/114298638-0d7dec80-9ad5-11eb-97b9-770c65e5dd3b.JPG)


**4. Root Mean Square Error using Surprise library**

![RMSE__1](https://user-images.githubusercontent.com/65005420/114298642-15d62780-9ad5-11eb-928e-f324eadaeb5d.JPG)


![RMSE__2](https://user-images.githubusercontent.com/65005420/114298645-18d11800-9ad5-11eb-98f4-b98a1c9f5c71.JPG)




**References**

B. Srebrenik, “Introduction to Music Recommendation and Machine Learning,” Medium, 04-Dec-2018. [Online]. Available: https://medium.com/@briansrebrenik/introduction-to-music-recommendation-and-machine-learning-310c4841b01d#:~:text=These%20music%20recommendation%20systems%20are,comes%20to%20a%20certain%20item.&amp;text=These%20two%20classes%2C%20or%20approaches,Filtering%20and%20Content%20Based%20Filtering. [Accessed: 17-Mar-2021].


“Using KNN algorithm for classification of textual documents,” IEEE Xplore. [Online]. Available: https://ieeexplore.ieee.org/abstract/document/8079924/?$casa_token$=35bn2HhwmIMAAAAA%3AVpJ_PGOtzqnKRqKBM68rdV0f81Kn73IUTSHMrOrPfXMVSMnNNbB68SDpo2i2shlczwjd7Dqd5lx6d8w. [Accessed: 17-Mar-2021]


C.-S. Mike Wu and D. Garg, “Movie Recommendation System Using Collaborative FilteringChing-Seh Mike Wu,” IEEE Xplore. [Online]. Available: https://ieeexplore.ieee.org/document/8663822. [Accessed: 17-Mar-2021].


A. Nguyen, “Singular Value Decomposition in Recommender Systems,” Home, 19-May-2016. [Online]. Available: https://repository.tcu.edu/handle/116099117/11320. [Accessed: 11-Apr-2021].


N. Hug, “Surprise: A Python library for recommender systems,” 05-Aug-2020. [Online]. Available: https://joss.theoj.org/papers/10.21105/joss.02174.pdf. [Accessed: 22-Mar-2021].
