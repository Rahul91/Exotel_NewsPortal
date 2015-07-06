# Exotel_NewsPortal

An online news portal by the community, for the community, to the community.

#Project Detail
A python-django based website, that lets user, watch news, add news and upvote there favourate content.
The project is up-and-running i.e. deployed on Heroku.
NewsPortal is the name of Project and News is the App.
    
    Link: http://community-news.herokuapp.com/


#Logic Flow
1. User visits, the home page of the website, he can register/login.
2. If Registered properly, he will be routed to Registered-Successfully page. Now he can click the link present in this page to login.
3. Thats it!!!. User can now add news and upvote there favourate news.
4. If loggedin, user may choose to logout, after which he will be routed to home page.

#Technologies Used

   1. Python(Core)
   2. Django(Framework)
   3. HTML(becasue, its needed!!!)
   4. CSS(Styling)
   5. JavaScript(For DOM Manipulation)
   6. Sqlite3(Database)
 
#Scope for Improvements

1. If a loggedin user, adds a content, then he is routed to home page, ideally he should be routed to his page. Need to correct this.
2. Once added a news, only admin can remove it. Ideally user who have added, should has authorization to edit it. This feature will soon be added.

 
#Cloning the repository

1. Create a virtualenv, activate it and get in:

            $virtualenv <env_name>
            $source <env_name>/bin/activate
            $cd <env_name>

2. Clone this repo into your machine by:

            git clone https://github.com/Rahul91/Exotel_NewsPortal.git

3. Install the dependencies using requirements.txt by:

            pip install requirements.txt

4. Thats, all, now you this website is up and runnig on your localhost. Just do:

            python manage.py runserver
 


#Bugs
In case of find any bug, feel free to clone it, replicate in your system, fix it and push to masters, or you drop a mail to priyrahulmishra@gmail.com
