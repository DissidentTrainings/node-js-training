# Node.js Training

Each Segment has 25 minutes and a 5 minute break. A day consists of 12 segemnts and takes up 6 hours. 

# Day I 

Introduces to node.js, npm and packages

## Part I 

### 01.01. Introduction and collection of objectives

Introduction to the training, the topic, the method and collection of participants objectives.  

### 01.02. How node works & why javascript 

An introduction to all the basic nuts and bolts of how node.js works and what implications this has.

* V8
* libev
* libeio
* npm 
* require.js 

### 01.03 Building and executing a basic node.js code

Fiddling around with node.js code to setup a little piece of code, execute it and grasp the basic handling.

* install a library 
* use require to load a module 
* know the order where require looks for files 
* execute the app 
* let the app write to std.io 

### 01.04 Networking and async stuff

How is http traffic handled in node js? How to access the request, write to the response and do all this in a async fashion. 

* Open port 80 
* Wait for a request to come in 
* log the ip of the request
* write  async function
* request and response object 


### 01.05 Data Access with REDIS

Use redis to demonstrate how to interact with external data storages. While we are at it we will configure it with environment variables. 

* Configuration via environment variables
* a crud application 
* memory vs. HDD vs. Network Speed 
* Using a external library for redis

### 01.06 Recap, lessons learned and QA

Collecting all the important learning points, cluster them and talk them through.

## Part II 

### 01.07 Debugging a node application

Sometimes a debugger attached to a node application can be a good thing. We will set it up and try using it. 

* node debugger
* Debugging in the IDE

### 01.08 managing multiple instances

Multiple node instances need to be managed in order to adhere to node.js technical nature. You want to swan multiple instances to use multiple cores of the cpu. The cluster modules does that for you. 

* using cluster

### 01.09 monitoring node apps

Logging actions and performance can be a pain. New relics services help greatly here. We will set up one, configure it and get through the basic stats.  

* using new relic

### 01.10 Coding Dojo I 

### 01.11 Coding Dojo II 

### 01.12 Lessons learned & questions

Another recap and new lessons learned.

# Day II 

* TDD (mocha) 
* Travis (CI)
* Grunt / Gulp 

## Part III


### 02.01 Intro and planning of the day


### 02.02 Node.js build tools  

A short review of gulp and grunt, the build tools in the node.js world. We will review 2 solutions and see how each of them works and how they are differnt from each other. 

* gulp / grunt 
* why a build tool

### 02.03 Git(hub) development workflow 

Versioning via git tags and installing a module with a special version directly via git/github. 

* using tags as versions 
* build, bump version and release 

### 02.04 TDD

TDD is strong in node. So we check out mocha, a Unit Test module for node.js. Additionally we will have a look into chai, a assertion library to fill all your needs for any assert style out there. 

* mocha 
* executing tests 
* async tests 
* assertion libraries 
* other test framework options 

### 02.05 creating a own module

NPM can be a pretty good helper to creat node.js/commoJS modules. In order to check it out, we will create a basic module and start versioning it. 

* initializing
* adding the right information 
* pushing to github 
* Readme 
* Versioning 
* installing with npm and a external github repo 

### 02.06 Recap, lessons learned and QA

## Part IV

Building a simple web app

### 02.07 Web development 

Express.js lets you create web applications and comes with a nice scaffolding init. We will check that out, start-stop it and add a new route. 

* Express.js 
* adding a route
* starting / stopping a app 
* anatomy of and express app 

### 02.08 Connect  

Connect provides easy to use and pre-defined modules to mess wit requests. Authentitcation, input filtering all done with connect. 

### 02.09 request and response

### 02.10 Express.js Coding Dojo 

### 02.11 Express.js Coding Dojo 

### 02.12 Lessons learned, QA and resolutions