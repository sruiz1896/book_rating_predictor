The Problem area: 


I would like to make a project that predicts a book’s rating score from written rating summaries.  I plan for this project to be a stepping stone toward a book recommender system for students struggling to choose their next book for programs such as Accelerated Reader. From my experience working at an elementary school, this can be a fun, interactive way for students to better acquaint themselves with literature.  


The User: 


This project would benefit people struggling to choose the next book to read. Specifically, this may aid those who want to explore titles beyond their knowledge, yet within their interests. This can reduce the amount of time spent on reading through reviews, allowing more time for reading actual content. 




The Big Idea: 


A machine learning categorical prediction can be used to answer the problem statement, “Can we use customer book review comments to predict the book’s rating score?” The target variable is the book’s (average) rating score. Following EDA (see ‘EDA’ notebook) is the biggest step needed to reach this goal: NLP in the form of text embedding and sentiment classification. 
Following this is creating the model and testing. (WIP)




The Impact: 


As stated above, my ultimate goal is to have this project be used as a book recommender system for students. As such, this can potentially be onboarded by schools or school districts as a way to promote student reading. This also has universal design potential, simplifying or streamlining options for readers. 


The Data: 
(https://www.kaggle.com/datasets/mohamedbakhet/amazon-books-reviews/data)
From source:
The first file** reviews** file contain feedback about 3M user on 212404 unique books the data set is part of the Amazon review Dataset it contains product reviews and metadata from Amazon, including 142.8 million reviews spanning May 1996 - July 2014.
and this file has these attributes


FILE 1: “BOOKS RATING”
Features                Description
id                        The Id of Book
Title                        Book Title
Price                        The price of Book
User_id                Id of the user who rates the book
profileName                Name of the user who rates the book
review/helpfulness        helpfulness rating of the review, e.g. 2/3
review/score                rating from 0 to 5 for the book
review/time                time of given the review
review/summary        the summary of a text review
review/text                the full text of a review


FILE 2: “BOOK DATA”
From source:
The second file Books Details file contains details information about 212404 unique books it file is built by using google books API to get details information about books it rated in the first file
and this file contains


Features                Description
Title                        Book Title
Descripe                decription of book
authors                Neme of book authors
imageurl                  for book cover
previewLink                link to access this book on google Books
publisher                Name of the publisheer
publishedDate                the date of publish
infoLink                link to get more information about the book on google books
categories                genres of books
ratingsCount                averaging rating for book


Please refer to ‘EDA’ notebook for further data insights


Notebooks:
EDA
(WIP)


Environments:
WIP