# The Gallery

##### By Brian Jomo.

### It is a description of the Quriousquest Blog.


## Table of Content

+ [Description](#description)
+ [Installation Requirement](#Installation)
+ [Technology Used](#technology-used)
+ [Reference](#reference)
+ [Licence](#licence)
+ [Authors Info](#author-Info)


## Description

This project involves creating a gallery website where web visitors can view a variety of images and a slight description. Web visitors can also copy the link of the image and share it if required.


## Installation

To gain acess to this application click on this link: https://github.com/BrianJomo/Image-Gallery

### Requirements

* Either a computer,phone,tablet or an Ipad.

* An access to the Internet.


### Installation Process

To access this application, type the following command in your terminal to have a local copy of the application.
```
https://github.com/BrianJomo/Image-Gallery.git
```
and for SSH, use the following command;
```
git@github.com:BrianJomo/Image-Gallery.git

```
Then run the following commands in the terminal then run the manage.py file in order to run the web application.

```
$ python3.8 -m venv --without-pip virtual

$ source virtual/bin/activate

$ curl https://bootstrap.pypa.io/get-pip.py | python

$ pip3 install -r requirements.txt 

$ python3.8 manage.py check

$ python3.8 manage.py makemigrations <installed app name>

$ python3.8 manage.py sqlmigrate <installed app name> 0001

$ python3.8 manage.py migrate

```
