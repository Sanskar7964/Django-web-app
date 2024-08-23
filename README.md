# Django responsive app with MYSQL database Project.

Greetings, I've completed the assignment I was asked. I have tried replicating the project as is from the tutorial which includes all the features. A key feature of my version of the project is the database configuration. I have implemented a mysql databased as compared to postgresql which was in the tutorial. 

Every part of this project is sample code which shows how to do the following:

- Use an embedded default django web server.
- Create a simple REST API that serves travel destinations exploring.
- Use of django admin panel to command application responsive features.
- Connect to a mysql database server which stores all the modelled details of the newer features.

## Watch the demonstration of the application here:

<a href="https://youtu.be/dsvW_-Iap-E" target="_blank">
<img src="https://i.ytimg.com/vi/BklkiDfcPkY/hqdefault.jpg" alt="Watch the series" width="240" height="180" border="10" />
</a>


## How to install this project on your local machine.
The easiest way to see how this works is to watch the demo, but here's the short version.

1. clone this project
2. Set up a local environment and install django - https://docs.djangoproject.com/en/5.1/topics/install/ 
3. Install Postgresql or mysql - https://dev.mysql.com/doc/mysql-installation-excerpt/5.7/en/
4. Configure your database details in settings.py
5. Install pillow for image assets processing.
6. Run the following commands:- python manage.py runserver-> python manage.py makemigrations-> python manage.py migrate.
7. Run the server again using the command python manage.py runserver use the localhost server `http://127.0.0.1:8000/` and surf the website.

## A little about python django architecture.
The MVT (Model View Template) is a software design pattern. It is a collection of three important components Model View and Template. The Model helps to handle database. It is a data access layer which handles the data.

The Template is a presentation layer which handles User Interface part completely. The View is used to execute the business logic and interact with a model to carry data and renders a template.

Although Django follows MVC pattern but maintains it?s own conventions. So, control is handled by the framework itself.

There is no separate controller and complete application is based on Model View and Template. That?s why it is called MVT application.
