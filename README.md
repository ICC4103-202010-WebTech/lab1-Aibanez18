3.3 How is the list of news articles structured with HTML?

The articles are structured in a thread using a <tbody> element which contains groups of three <tr> elements which in turn contain:
1.<td> elements with an index, vote button, name of the post and an external link.
2.<td> elements with details about the post like number of votes, original poster, comments, etc.
3.A spacer between articles.

3.4 Briefly describe what you see in files with names starting with hn.js and news.css. How are these files different? What is their purpose?

hn.js is a java script that appears to be a library of the functions used by the page such as voting or adding new stories. 
news.css on the ther hand appears to be a stylesheet with the page's assets like layout, fontsize, color and images.
They are different in that the former looks more interaction focused while the latter is just the aesthetic part.

3.5 How many requests has it taken for the browser to download the Hacker News main page? What are the HTTP request methods in each case?

Seven resources were downloaded when refreshing the site, mostly images and the two files from part 3.4. 
All resources use the GET method as we are just requesting data and not sending any.