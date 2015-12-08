---
layout: page
title: How To
subtitle: How to submit posts
permalink: /howto/
---
# Getting started with Posting to the GGA Page

## 1. Sign up with Github
![](https://images.duckduckgo.com/iu/?u=http%3A%2F%2Fwww.molecularecologist.com%2Fwp-content%2Fuploads%2F2013%2F11%2Fgithub-logo.jpg&f=1)

<br>
Sign up at [github.com](https://github.com/)

## 2. Send your github id to the site admin (whoever that is at the moment):

![](https://avatars3.githubusercontent.com/u/3622055?v=3&s=460)
Send <a href="mailto:joseph.lee@geog.ubc.ca">Joey</a> an email


***

*At this point, you've all now been added as collaborators to the [ubcgga github account](https://github.com/ubcgga) and can begin posting to the webpage*

***


## 3. Log in to Github and go to [where the GGA Webpage Lives](https://github.com/ubcgga/ubcgga.github.io) and let's add a post

* Enter the repository:

![](../assets/images/repo001.png)

* Of all the folders and things we see in there, what we're interested in is the ```_posts``` folder:

![](../assets/images/repo002.png)

* Inside the ```_posts``` folder we have all of our posts (yes - very new concept). 
![](../assets/images/posts001.png)

* Notice that each post is labeled as such: 

		YYYY-MM-DD-title-separated-by-dashes.md
		
	where:
	
	* **YYYY**: the year (e.g. 2015)
	* **MM**: the month (e.g. 12)
	* **DD**: the day (e.g. 08)
	* **title-separated-by-dashes**: the title (e.g. my-lonely-geography)
	* **.md**: the type of file - markdown! 

* this is how we will name our posts :)

* To add a file click ```New file```
![](../assets/images/posts002.png)

* Now we can get taken to a new page where we can add our post:
![](../assets/images/posts003.png)

* where it says: ```name your file...``` put your title as we described above
* where it says ```edit new file``` we're going to put our post.

## The components of a post:

* So we have our post:
![](../assets/images/posts004.png)

* What absolutely needs to go into the top of the post is this - the "frontmatter":

		---
		layout: post
		title:  "My Post Title"
		subtitle: "My Post Subtitle"
		date:   YYYY-MM-DD 12:00:00
		categories: [gga, resources]
		---
	where:
	
	* layout: post
	* title:  the title of your post
 	* subtitle: the subtitle of your post
	* date:  the date/time when you posted in  ```YYYY-MM-DD 12:00:00```
	* categories: the categories the post fits into ```separated by commas``` - here we have ```[gga, resources]```, but you might have ```[advice]``` or ```[tools, resources]```, etc.

![](../assets/images/posts005.png)

* under the frontmatter, you can write whatever you'd like! 

		I <3 geography

## LAST: ```commit new file``` and BOOM! see the magic at [ubc.github.io](http://ubcgga.github.io/)
![](../assets/images/posts006.png)


<br>
<br>
*** 
***An Optional Step***
## 2.5. Get a markdown editor 
The posts are written in [markdown]() which we might conceptualize as the beautifully simple to use love child created from the union between plain text and html. 

***IT IS AWESOME***

Among the many things that markdown is great for - like taking notes, and even making standalone webpages - is that our blog posts are written in markdown :) 

Markdown is free and there are lots of nice markdown editors out there like:

### [Mou](http://25.io/mou/) for OSx
![](http://25.io/mou/images/1.png)


### and Windows
![](http://www.markdownpad.com/images/markdownpad2.png)
[Markdown Pad](http://www.markdownpad.com/)

***




<!--# Setup

## (temporary)
1. log in to Github
( you'll have to be added as a collaborator first! so send your github id name to: joseph.lee@geog.ubc.ca) 
2. go to "_posts" folder
3. add a new file click "new file"
4. title format:   YYYY-MM-DD-title-separated-by-dashes.md
5. include a "frontmatter": this is where you can put the category tags in etc.


		---
		layout: post
		title:  "My first post"
		subtitle: "Woohoo!"
		date:   2015-12-04 23:34:01
		categories: [gga, resources]
		---


 6. After the front matter, put in your text:
 
 

		 Our first post in the gga blog. Geography is the best/worst thing ever! 


6. click "commit" new file.
7. Go see the magic at: [http://ubcgga.github.io/](http://ubcgga.github.io/)

-->