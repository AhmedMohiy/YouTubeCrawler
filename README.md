# YouTubeCrawler


![YouTubeCrawler](http://www.tubefilter.com/wp-content/uploads/2016/06/youtube-gears.jpg)


# What it is?

This application help you to crawel YouTube channel or playlist


# What I used to creaet this application

1. python 2.7
2. Django 1.11
3. python-pafy 0.5.3.1
3. ubuntu 16.04


# Setup the project

First you need to install django you will find how in this link
```
https://www.digitalocean.com/community/tutorials/how-to-install-the-django-web-framework-on-ubuntu-14-04
```
Then you you need install python-pafy

```
sudo apt-get update
```

### for python 2.x

```
sudo apt-get install python-pafy
```
or  by pip
```
sudo pip install pafy
```

### for python 3.x

```
sudo apt-get install python3-pafy
```
or  by pip
```
sudo pip3 install pafy
```


# How it works ? #

When you run the project this page will appear for crawling videos

### For crawling channel 

you must write channel url in the text field then choose channel radio button then hit submit  
  link like:

```
https://www.youtube.com/user/AsapSCIENCE
```
### And for crawling playlist 

write PlayList url in the text field then choose playlist radio button then hit submit  
 link like:
```
https://www.youtube.com/watch?v=ztiHRiFXtoc&list=PLvFsG9gYFxY_2tiOKgs7b2lSjMwR89ECb
```

## Home page :

![Home](http://oi63.tinypic.com/hrbszc.jpg)

## View videos :

This page will retrieve the videos from the database and view it, 
  you get to this page by clicking on view tap at the top of tha page.
![View](http://oi63.tinypic.com/2625y14.jpg)


## Video details :

This page will show you the video details after you clicked on the details button in the view page  
what you can do here  

1. Watch the video by clicking on Watch on YouTube button
2. you can download the video

![Deatails](http://oi68.tinypic.com/w12zkj.jpg)

## After download

After you clicked the Download button this page should appear

![after download](http://oi66.tinypic.com/2yjq8nb.jpg)

## Finally

##### ok that's it for now i hope you enjoy it.
### Thank you.



