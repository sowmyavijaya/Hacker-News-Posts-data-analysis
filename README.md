# Hacker-News-Posts-data-analysis
Analysing the ask posts and show posts in Hacker News posts dataset

In this project, a data set of submissions to popular technology site Hacker News has been used. Hacker News is a site started by the startup incubator Y Combinator, where user-submitted stories (known as "posts") are voted and commented upon, similar to reddit. Hacker News is extremely popular in technology and startup circles, and posts that make it to the top of Hacker News' listings can get hundreds of thousands of visitors as a result.

Below are descriptions of the columns:

* id: The unique identifier from Hacker News for the post
* title: The title of the post
* url: The URL that the posts links to, if it the post has a URL
* num_points: The number of points the post acquired, calculated as the total number of upvotes minus the total number of downvotes
* num_comments: The number of comments that were made on the post
* author: The username of the person who submitted the post
* created_at: The date and time at which the post was submitted

The dataset has been reduced from almost 300,000 rows to approximately 20,000 rows by removing all submissions that did not receive any comments, and then randomly sampling from the remaining submissions.

The analysis answers 2 questions:
1. Which type of posts - Ask HN or Show HN receive more comments on average?
2. What is the hours of the posts created time which receive more comments on average?

Imported modules : csv, datetime
