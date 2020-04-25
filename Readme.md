# Readme
# DB Project --Data Visualization Job
#   
#  

### Tong Yang 001302930
### Minghao Ru 001088106
#### Portfolio github link:https://github.com/yangtong951019/InfoINFO6210_Data_Jobs_Final_Project


[![N|Solid](https://www.glassdoor.com/blog/app/uploads/sites/2/glassdoor-offices-chicago-valerio-dewalt-train-associates-8-700x462.jpg)]

This documentation is try to show what's contain in different file in this zip file.

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Our project is a formal-made Database of 'Data Visualization' jobs

  - Web scraping the data from job-searching website (we choose Glassdoor).
  - Making the job data full of details of the job.
  - Converting data to .csv files as a start of a datebase file.
  - Cleaning and integration the job data to make it usable.
  - Using API to connect to Social Media like Twitter to grab some tag and tweets about the related jobs.
  - Converting this social media data into .csv files.
  - Using Python to make all the data compile into a database like .db file.

# Features

  -  Scrape the data of job and make it clear to use.
  -  Get some information about the related jobs on social media in order to see people' attitude towards these jobs.
  -  Make the job data and the social-media data into database.
  -  Optimize and operate the database.


You can also:
  - Output the other job title result as .csv files
  - Search whatever jobs or cities that the job belongs to
  - Use the salary to compare and rank the job you want



> We use Glassdoor search result of 10 cities in our project.
> (In each row, we have Name, Company, State, City, Salary, Location and the Url of this job, please check it in our data files which is like CITYNAME-Data Visualization-job-results.csv)

Bingo!

# Guide of our portfolio

### Report File：

It include our 'report.docx': It's a report of the whole project, containing output of code and MYSQL queries results.

## Project:
### Code file:
- getJobData.ipynb: This is the python file to web scraping the requested 300 jobs data from Glassdoor
- socialMediaAPI.ipynb: This is the python file to grab the social media data with API about the related jobs and generate the databases and execute them

### ER-diagram file:
ERD.png（ER Model of project）



# Tech and Concept

We use a number of open source projects to work properly:

* [Requests] - Core concept for our system
* [Commons Math] - The important package we use to do the math work
* [.csv] - The result's format we chosse
* [Glassdoor] - The job search website to get job information




# Usage


Install the dependencies and devDependencies and start the server.

For web scraping the data...
```sh
$ import pandas as pd
$ import re
$ import urllib.request
$ import requests
$ from bs4 import BeautifulSoup
```

For get data from social media with API...

```sh
$ import tweepy
$ import json
$ import datetime
$ import warnings
```



# Development


Core package:
```sh
$ import requests
$ from bs4 import BeautifulSoup
```

imports:
```sh
$ import pandas as pd
$ import re
$ import urllib.request
$ import requests
$ from bs4 import BeautifulSoup
$ import tweepy
$ import json
$ import datetime
$ import warnings
```




### Kubernetes + Google Cloud

See [KUBERNETES.md](https://github.com/joemccann/dillinger/blob/master/KUBERNETES.md)


## Todos in future

 - Use salary to filter the jobs we want
 - Use the existing data to predict the data we want

Licenses
----

MIT


**Thank you! Have a nice day and stay safe!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)



   [df1]: <http://daringfireball.net/projects/markdown/>
   [.csv]: <https://en.wikipedia.org/wiki/Comma-separated_values>
   [Commons Math]: <http://commons.apache.org/proper/commons-math/index.html>
   [Glassdoor]: <https://www.glassdoor.com/member/home/index.htm>
   [Requests]: <https://realpython.com/python-requests/>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
