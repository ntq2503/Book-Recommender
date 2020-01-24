# Book-Recommender

Recommender systems are implemented everywhere on the Internet. Given the gigantic amount of data available online and the limited time and visualization humans have, these systems play a crucial part in facilitating data transfer and maximize satisfaction rate of Internet users. The potential output is an algorithm that takes a book title and return a group of recommended books.

The dataset consists of 3 table files: books information, books ratings and users information. Books information include the title, book ID, author, year, publisher and some links to images. Books ratings includes user ID, book ID and the rating. User information include user ID, age and location.

I choose to use both a supervised algorithm Matrix Factorization and an unsupervised algorithm K-Means. These 2 methods are commonly used for recommemder systems. At the end, I would like to compare the results from the 2 methods to determine if they are consistent.

The results show slight overlap between the 2 different methods. However, the difference is significant. The consistency could be improved if more factors are considered such as age, location, author, etc.

After all, effectiveness of a recommender system is typical measured by number of users' clicks. This data can be extremely helpful in improving the performance. A good recommender system tends to be one that has been used for long enough to predict trends in users behavior.
