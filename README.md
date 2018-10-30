# Title: Is there a connection between a book's cover and its content ?

# Abstract
The idea of this project is to investigate on the Amazon data concerning their product's reviews and especially on the book. We focus on the idea to not judge a book by its cover. In fact, when we buy a book on Amazon, we get only access on its cover and not on its content, however we get access to its reviews, in fact, these reviews encourage or discourage the potential buyer to buy the product. Then the goal of this project is to find a correlation between the book cover and its reviews. For our investigation, we use the Amazon data set from te webiste http://jmcauley.ucsd.edu/data/amazon/ where we extract the books reviews, their ratings and their image representing the covers. In two last mentionned have also their importance to influence the potential buyer. During this project, we study the the influence of features on the buyer so that he buys the book or not.  

# Research questions
- Study the cover of each books and their features. 
- Study the words of each reviews to determine if it is a positive or a negative review.
- Study the correlation between between the book's cover and its review.
- Study the link between the rating and the reviews.

# Dataset
Since we need the reviews and the ratings of the books, then we use the datasets containing these features, the reviews are contained in the file reviews_books_5.json.gz and the ratings in the file ratings_books.csv. We need also the datasets image features containing the cover of the book for the book's cover study. The dataset with the metadata will also be used in order to get additional information on the book such as its description, its sales-rank and its price.

# A list of internal milestones up until project milestone 2
For the analysis, we first proceed in the Data wrangling to get the dataset clean and also merge some datasets together such as the reviews and the ratings of the book. Since this procedure end, we analyze the average ratings to see which is the most used rating by the buyers. We proceed then in a selection on the features that might be the most relevant for our analysis. Then we apply machine learning methods to do some text analysis for reviews to determine which reviews are positive or negative. The next step is to obtain the books cover and to proceed on image processing, we apply machine learning methods to extract the features of each cover to determine, and then we analyze the feature of the most bought book, for example the color, the draw, the title. Finally, we try to find a correlation between the image and the reviews to see which feature incluences te most the buyers.

# Questions for TAa
Add here some questions you have for us, in general or project-specific.
