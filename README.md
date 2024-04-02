### INF601 - Advanced Programming in Python
### Austin Howard
### Mini Project 3


# Mini Project 3 (Liftr)

## Description

This is an introductory project to learn how to leverage flask to design a basic web application.  

I want to create a webapp wherein users can post about their workouts in a blog-type format. They should be able 
to include which exercises they performed, reps, weight, etc.

Additionally, these new concepts are introduced to the course from this project:
* SQLite Database configuration and integration
* HTML templating and extension
* Stylesheets
* Leveraging Bootstrap for GUI design

This project serves as a proof of concept for the structure of a web app and isn't designed to showcase a viable 
product.

## Getting Started

### Step 1: Pip Install Requirements

In order to use this application you must first install its dependencies.  

In a terminal window, please type the following:
```
pip install -r requirements.txt
```

### Step 2: Initialize the Database

Before using the website you must initialize the database so that get/post remains functional.  

In a terminal window, please type the following:
```
flask --app liftr init-db
```

### Step 3: Executing the program
You can now initiate the developmental server for Liftr.

In a terminal window, please type the following:
```
flask --app liftr run
```

## Authors 

Austin Howard - [Email](a_howard4@mail.fhsu.edu)

## Version History

* 1.0
    * Initial Release to complete the assignment

## License

This project is licensed under the GNU General Public 
License (Version 3).  

See the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, etc.
* [Jason Zeller's Youtube Playlist](https://youtube.com/playlist?list=PLE5nOs3YmC2THmgcLi-ogD8KiIfCjS06V&si=Jxm455HAtPZkZZ3Q)
* [Flask](https://flask.palletsprojects.com/en/3.0.x/)
* [Bootstrap 5.3](https://getbootstrap.com/docs/5.3/getting-started/introduction/)