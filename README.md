# Social Book App using Django (python web-development framework)

Pre-Conditions: Python3 and pip3 are already installed. All instructions are based on Mac OS

1) Install Django: pip3 install django


2) Install a Project:

    a) Create a workspace folder. If you are in Mac, open a terminal and by default you will be under users\<username> directory
    
    b) This is an example of how your project folder will look like: Macintosh HD⁩ ▸ ⁨Users⁩ ▸ ⁨username ▸ ⁨workspace⁩ ▸ ⁨Django⁩
    
    c) Run this command to create a Project: django-admin startproject social_book
    
    d) After Installation, the folder structure will look like this:
    
        workspace\Django
    
          \social_book
    
              \social_book
    
                  \*.py
  
    
3) Install an App: Think of an App as feature. e.g. Notifications, email service, etc. We will create an App name core

    a) Navigate to the highest folder level of your peoject. In this case Django\social_book
    
    b) Run this command to create an App: django-admin startapp core
    
    c) After Installation, the folder structure will look like this:
    
    
    workspace\Django
    
          \social_book
          
          \core
          
            \*.py
    

4) Run Server: Once you follow the above steps, to ensure that you have installed correctly, just start the server and navigate to the url

    a) Navigate to the folder where you have the file manage.py and run the following command: python3 manage.py runserver
    
    b) Launch your browser and copy-paste the url: e.g. http://127.0.0.1:8000/
    
    c) you will see a page indicating successful installation

