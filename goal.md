[CO-ERA](http://www.co-era.com)

#Web analytics using elasticsearch

#Statement of intent
This project is a Proof of Concept. The goal is to implement web analytics functions using elasticsearch. The information to be analyzed is collected from the incomming http requests to a web site.

There are a series of questions that will be answered:

1. How many visitors were on the web site during a specified period {last day, last week, last month, last year}?
2. Top 10 most visited pages. How much of the traffic is driven by top 10 pages. Which pages drive 50% of the visits?
3. Top 10 least visited pages. How many pages were not visited.
4. Are all pages of the web site crawled by the search engines bots?
5. How often are the pages crawled and by which bots?
6. Which pages are trending up and down?
7. Which external and internal referrers drive most of the traffic?
8. Which pages are visited together?
9. Distribution of the visitors based on the device and web browser?
10. Display long tail of pages visited.
11. Geographical distribution of the visitors.

The answers will be provided as a series of charts in a web application. Correlated information will be displayed in the same web pages as a dashboard.

The application will be able to store information from multiple domains.

Web analytics trackers are not in scope of this project.

#Statement of work
The application will be implemented using .net framework libraries and c# language. 
Visual Studio 2013 will be the development tool.
The code base will be hosted on a public repository on github [repolink](https://github.com/CO-ERA/Web-analytics-elasticsearch)
The log is going to be delivered as a text file? (or json).

The application design will be documented and explained.

1. Structure of data stored in elesticsearch.
2. How data is loaded into elasticsearch.
3. The searches and variability factors.
4. Data visualisation and user interaction (filters, sorting, navigation).

Sample data will be created by anonymization of the data collected from a real life project.

It is possible that not all the questions from the Statement of intent can be answered. For the ones that cannot be answered a rational and alternative solution will be described.

#Results
Work in progress.
