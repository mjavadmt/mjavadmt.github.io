---
layout: posts
title: Hackaton
---
# project name :
* work advertisements
<br/>
# project idea :
* this idea came to my mind because in these days people can't find job easily and have too problem to find their favourite job . <br/>
<br/>
# the way I execute and desing project :
* first in model.py i modeled things that the clients should fill out like their name , their location , job category , ... 
<br/>
* then in the views.py i described functions and their duties that has 2 part :
    - first part: get method ==>> clients just get information <br/>
    - second part: post method ==>> clients fill out the form for the other observer who wants to get a job <br/>
in get method i move them toward the category the want <br/>
* then urls.py that each job have its unique url and when the clinet push for example computer in goes to computer url and render computer.html<br/>
* and templates with .html suffix that has the structure of the site and beautify it . in templates i have some html files that are jobs in each one i made a table for job to be in good order . <br/>

# some pictures of my website

# first page :
![image of soloving]({{mjavadmt.github.io}}/assets/images/django.png)
* on the top of the page if you're looking for a job you can pick one of these categories and find your favourite job<br/>
* on the bottom of the page if you're employer you can fill out the form for employees in specified category to be convinient for them to find job.<br/>
# each job page :
![image of soloving]({{mjavadmt.github.io}}/assets/images/computer.png)
* on the top of each page i insert a picture that matches to job
* then i made a table which is made by the data that employers filled. in the table has 5 topic just like the form on the first page . if employer for instance choose the computer category one row will be added on the bottom with its data(like phone number,jobname,location,..) <br/>
![image of soloving]({{mjavadmt.github.io}}/assets/images/art.png)
<br/>
![image of soloving]({{mjavadmt.github.io}}/assets/images/elec.png)






---
