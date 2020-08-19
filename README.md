# Trends-in-Programming-Languages
We’re always staying on the pulse of the software development industry so that we can better prepare our students for rapidly – changing technology job market. Many of the students and developers in general are interested in working at top startups and tech companies. How can we tell what programming languages and technologies are used by the most people? How about what languages are growing, and which are shrinking so that we can tell which are most worth investing time in?

One excellent source of data is Stack Overflow, a programming question and answer site with more than 16 million questions on programming topics. By measuring the number of questions about each technology, we can get an approximate sense of how many people are using it. We're going to use open data from the Stack Exchange Data Explorer to examine the relative popularity of languages like R, Python, Java and JavaScript have changed over time.

Each Stack Overflow question has a tag, which marks a question to describe its topic or technology. For instance, there's a tag for languages like R or Python, and for packages like ggplot2 or pandas.
	
The dataset used, contains one observation for each tag in a year. The dataset also includes both the number of questions asked in that tag in the year and the total number of questions asked in that year
Rather than just the counts of the tags, the concern here is the percentage change: the fraction of questions that year have that tag

# What are the most asked - about tags? 
It's sure been fun to visualize and compare tags over time. The dplyr and ggplot2 tags may not have as many questions as R, but we can tell they're both growing quickly as well.

We might like to know which tags have the most questions overall, not just within a particular year. 

#The TIOBE Programming Community index is an indicator of the popularity of programming languages. The index is updated once a month. The ratings are based on the number of skilled engineers world-wide, courses and third-party vendors. Popular search engines such as Google, Bing, Yahoo!, Wikipedia, Amazon, YouTube and Baidu are used to calculate the ratings. It is important to note that the TIOBE index is not about the best programming language or the language in which most lines of code have been written. (https://www.tiobe.com/tiobe-index/)



# Comparing R and Python
There is a lot of heated discussion over the topic, but there are some great, thoughtful articles as well. Some suggest Python is preferable as a general-purpose programming language, while others suggest data science is better served by a dedicated language and toolchain. The origins and development arcs of the two languages are compared, often to support differing conclusions.



For individual data scientists, some common points to consider:

* Python is a great general programming language, with many libraries dedicated to data science.
* Many (if not most) general introductory programming courses start teaching with Python now.
* Python is the go-to language for many ETL and Machine Learning workflows.
* Many (if not most) introductory courses to statistics and data science teach R now.
* R has become the world’s largest repository of statistical knowledge with reference implementations for thousands, if not tens of thousands, of algorithms that have been vetted by experts. The documentation for many R packages includes links to the primary literature on the subject.
* R has a very low barrier to entry for doing exploratory analysis, and converting that work into a great report, dashboard, or API.
* R with RStudio is often considered the best place to do exploratory data analysis. (https://blog.rstudio.com/2019/12/17/r-vs-python-what-s-the-best-for-language-for-data-science/)
