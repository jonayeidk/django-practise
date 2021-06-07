# django-practise

# Creating a project 
  
    django-admin startproject PROJECTNAME

Go to proejct directory run the following commands:
    
    python manage.py runserver
  
# You’ll see the following output on the command line:

    Performing system checks...

    System check identified no issues (0 silenced).

    You have unapplied migrations; your app may not work properly until they are applied.
    Run 'python manage.py migrate' to apply them.

    June 05, 2021 - 15:50:53
    Django version 3.2, using settings 'mysite.settings'
    Starting development server at http://127.0.0.1:8000/
    Quit the server with CONTROL-C.
    
  
# Now that the server’s running, visit http://127.0.0.1:8000/ with your Web browser. 

# Changing the port 
  If you want to change the server’s port, pass it as a command-line argument.
  
     python manage.py runserver 8080 
 
  If you want to change the server’s IP, pass it along with the port. 
  
    `python manage.py runserver 0:8000
    
# To create your app, make sure you’re in the same directory as manage.py and type this command:

    python manage.py startapp polls
    
    
That’ll create a directory polls, which is laid out like this:

    polls/
        __init__.py
        admin.py
        apps.py
        migrations/
            __init__.py
        models.py
        tests.py
        views.py
    
This directory structure will house the poll application.
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
