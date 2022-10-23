Play Store App Review Analysis
Abstract:
We are analyzing the data of playstore apps and user reviews.Our objective is to Actionable insights that can be drawn for developers to work on and capture the Android market and key factors responsible for app engagement and success. We studied two data sets one in terms of app category , its size , no of installed , no of reviews ,its price , for whom these apps can suitable , genres app belong to , app last update, current version , for which android version it is suitable and another dataset is of user reviews in terms of user review , their sentiment ,sentiment polarity and sentiment subjectivity.
 Project Files Description:
This Project includes 1 colab notebook of individual, 1 team colab, 1 technical documentation,1 self video as well as 1 presentation :
Executable Files:
Play Store App Review Analysis - Includes all functions required for clustering operations.
Output:
Google Colab - All the outputs are visible in the provided colab notebook.
Input Files:
Play Store Data.csv - It contains the basic details of the app like number of user reviews, ratings, etc.
User Reviews.csv - It contains the user reviews and its sentiment score for the respective app.
Data Source:
Dataset - Dataset taken from Almabetter
Introduction:
Play store is an Android Market that serves as the official app store for certified devices running on the Android Operating system. Developed and Operated by Google, launched on 6th March, 2012. Approximately 3.48 million apps are in the Play store. Play store apps have their own features such as Ratings, Reviews, Size and more. From the problem statement given, we should analyze the given database and should come up with the key factors that increased the number of users, long term usage etc., the objective of this project is to deliver insights to understand customer demands better and thus help developers to popularize the product.
The contents of Play Store Data are:
App: It contains the name of the app with a short description (optional).
Category: This section gives the category to which an app belongs. In this dataset, the apps are divided among 33 categories.
Size: The disk space required to install the respective app.
Rating: The average rating given by the users for the respective app. It can be in between 1 and 5.
Reviews: The number of users that have dropped a review for the respective app.
Installs: The approximate number of times the respective app was installed.
Type: It states whether an app is free to use or paid.
Price: It gives the price payable to install the app. For free type apps, the price is zero.
Content rating: It states which age group is suitable to consume the content of the respective app.
Genres: It gives the genre(s) to which the respective app belongs.
Last updated: It gives the day in which the latest update for the respective app was released.
Current Ver: It gives the current version of the respective app.
Android Ver: It gives the android version of the respective app.
The contents of User Reviews are:
App: It contains the name of the app with a short description (optional).
Translated_Review: It contains the English translation of the review dropped by the user of the app.
Sentiment: It gives the attitude/emotion of the writer. It can be ‘Positive’, ‘Negative’, or ‘Neutral’.
Sentiment_Polarity: It gives the polarity of the review. Its range is [-1,1], where 1 means ‘Positive statement’ and -1 means a ‘Negative statement’.
Sentiment_Subjectivity: This value gives how close a reviewer’s opinion is to the opinion of the general public. Its range is [0,1]. Higher the subjectivity, closer is the reviewer’s opinion to the opinion of the general public, and lower subjectivity indicates the review is more of a factual information.
 References
GeeksforGeeks
tutorialspoint
Stackoverflow
Python libraries documentation 


