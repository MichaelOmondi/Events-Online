# Events-Online
## Author 

>[MichaelOmondi](https://github.com/MichaelOmondi/Events-Online)

# Description

This is an applicatin thet tells the user about the events happening around the tech world

## Live Link

Click [] (https://mkevents.herokuapp.com/) to visit the site

## User Story

* Click on different photos to see the events which are hapening around the world

*  Search for different categories 

* View photos based on the location they were taken. 

## Cloing the repository:

##### Cloning the repository:  
 ```bash 
 https://github.com/MichaelOmondi/Events-Online
```
##### Navigate into the folder and install requirements  
 ```bash 
cd Picture-Globe pip install -r requirements.txt 
```
##### Install and activate Virtual  
 ```bash 
- python3 -m venv virtual - source virtual/bin/activate  
```  
##### Install Dependencies  
 ```bash 
 pip install -r requirements.txt 
```  
 ##### Setup Database  
  SetUp your database User,Password, Host then make migrate  
 ```bash 
python manage.py makemigrations pictures 
 ``` 
 Now Migrate  
 ```bash 
 python manage.py migrate 
```
##### Run the application  
 ```bash 
 python manage.py runserver 
``` 
##### Running the application  
 ```bash 
 python manage.py server 
```
##### Testing the application.  
 ```bash 
 python manage.py test 
```
Open the application on your browser `127.0.0.1:8000`.  
  
## Technoogy used

* [Python3.8](https://www.python.org/)  
* [Django 3.1.2](https://docs.djangoproject.com/en/2.2/)  
* [Heroku](https://heroku.com)  

## Known Bugs  
* Some functionalities did not wrk as expected




