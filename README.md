# Fun-With-D3

Fun with D3 explores fun features that can be unlocked with the awesome power of D3. The main goal of this course is to master D3.
--------------------------------------------------------------------------------
## TOC
### Prerequisites
### How It Works
#### Course overview
##### What is D3.js?
##### Why use D3?
#### Philosophy
### Getting Started
--------------------------------------------------------------------------------
## Prerequisites

There are a few things you'll need for this course.

* A text editor to edit and create HTML, CSS and JS files. We're using Atom
* A modern web browser (Firefox 3, IE 9, Chrome, Safari 3.2, and later)
* Local HTTP server to host data file for some advanced recipes in this course. We'll cover this in the first few lessons.

## How It Works

D3 is a JavaScript Library designed to display digital data in dynamic graphical form. Helps bring data to life using HTML, SVG, and CSS. d3 V4 is the latest release of the D3 library.

### Course Overview

In this course you will learn:

* Fundamental concepts of data visualization
* Functional JavaScript
* D3 fundamentals
  * Element selection
  * Data binding
  * Animation
  * SVG generation
* D3 Advanced Techniques
  * Interpolators
  * Custom tweening
  * Timers
  * Queueing
  * Hierarchy
  * Force manipulation


##### What is D3.js?

Data Driven Documents (D3) is an open source Javascript library used to create dynamic, interactive visualizations enabled on modern web browser. Runs mainly using HTML, SVG, CSS, Javascript.
D3 is extremely fast, responsive and supports large datasets for creating dynamic animations in web browsers.

##### Why Use D3?

You should use D3.js because it lets you build the data visualization framework that you want. Graphic / Data Visualization frameworks make a great deal of decisions to make the framework easy to use. D3.js focuses on binding data to DOM elements.

D3.js is written in JavaScript and uses a functional style which means you can reuse code and add specific functions to your heart's content. Which means it is as powerful as you want to make it. How you chose to style, manipulate, and make interactive the data is up to you.

##### Philosophy

D3 allows a person to visualize data. The Data Visualization process as a series of steps:

1. Acquire
2. Parse
3. Filter
4. Mine
5. Represent
6. Refine
7. Interact

_Acquire_

This is where we obtain the data, whether from a file on a disk or a source over network. This course will begin by manually generating data. Later, you will turn to existing data sets. Much later you we will cover scraping websites to find interesting unstructured data sets.

_Parse_

Provide some structure for the data's meaning, and order it into categories.

This is the most tedious aspect of working with data; the pre-processing of data into a collected structure. The structure will make it easier to convey to others what data you have by format, tags, names, and indices.

_Filter_

Remove all but the data of interest.

This is also part of the pre-processing process. After putting the data into a structure, you will have to filter out the data not necessary for Data Viz.

_Mine_

Apply methods from statistics or data mining as a way to discern patterns or place the data in mathematical context

_Represent_

Choose a basic viz model such as a bar graph, list, map or a tree.

_Refine_

Improve the basic representation to make it clearer and more visually engaging.
The focus here is Css3, HTML5 and SVG. Basics of color theory and graphic design theory will be covered.

_Interact_

Add methods for manipulating the data or controlling what features are visible.



## Lesson 1

In this lesson we will cover:
* Set up simple D3 dev environment
* Set up npm based D3 dev environment
* Understanding D3-style functional Javascript

This lesson is designed to get you up and running with D3.js and covers fundamental aspects, such as how to set up a typical D3.js data viz environment and a section devoted to covering lesser known areas of JavaScript that D3.js relies upon.

### Lesson 1-1 : Setting up a simple D3 environment

1. Download the latest stable version from [D3.js](https://d3.js.org)
2. Once it is downloaded and unzipped, you'll have both the ```d3.js``` and ```d3.min.js``` and other informational files. Use the ```d3.js``` file.
3. Place the ```d3.js``` file in the same folder as ```index.html```

ex: figure Lesson1-1

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Fun With D3!</title>
    <script type='text/javascript' src='d3.js'></script>
  </head>
  <body>

  </body>
</html>
```
### Lesson 1-2 : Setting up an NPM-based environment

1. create a folder and cd into the directory and make an ```index.html``` page
2. Within that folder, use the npm command ``npm init```
3. Once ```package.json``` is defined, you can run ```npm install```
4. install D3.js by installing the d3 npm module by running ```npm install d3 --save-dev``` then run ```npm install ``` again


### Lesson 1-3 : Setting up an local HTTP server

There are actually more than a dozen different ways to set up an HTTP server on your computer. We will cover the most popular setups.

#### Python Simple HTTP server
This is a favorite for development and fast prototyping. If you have python installed then you can simply type into the terminal *note different syntax based on python version* :
Python v2
```
> python -m simpleHTTPServer 8888
```

Python v3
```
> python -m http.server 8888
```

#### Nodejs HTTP server
If you have Nodejs installed, then you can simply install the ```http-server``` module from npm.

1. install ```http-server``` module by running ```npm install http-server -g```
2. Create a server from any folder using the command-line terminal by running:
```
http-server -p 8080
```

### Lesson 1-4 : Understanding D3-style Javascript

D3 is designed and built using functional style Javascript. This recipe is designed to cover some of the fundamental concepts in functional JavaScript required to make sense of D3.












## Resources:

[D3 Documentation](https://github.com/d3/d3/blob/master/README.md)

[D3 Wiki Tutorials](https://github.com/d3/d3/wiki/Tutorials)

[Interactive Data Visualization](http://alignedleft.com/tutorials/d3/)

[Square Intro to D3](https://square.github.io/intro-to-d3/)

[D3 First Steps](https://www.dashingd3js.com/d3js-first-steps)


## Contact

marco@marcopineda.com
