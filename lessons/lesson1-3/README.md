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
