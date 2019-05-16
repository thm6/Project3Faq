# Faq site 

Features we have: 
* Up and down votes button features for questions and answers  
* Features access Control for level of users  
* Database Notifications

This FAQ webpage has features like Q&A forum websites. 

## Getting Started on this project 

**Clone here:**  

git clone: https://github.com/thm6/Project3Faq.git

### Composer:  

```  
CD into FAQ and run composer install  
```  
### Installing .env file  
``` 
cp .env.example to .env  
```  

### Database Setup  

```  
Setup sqlite database  
```  
### Generate artisan key  

``` 
php artisan key:generate  
Migrate php artisan migrate  
```  

## Epic: Features 3 levels of Access roles for the user & adding up-vote and down-votes to questions and answers  
1. Super Admin  
2. Admin  
3. Member (we use this role in this project)  
![theRoles](https://user-images.githubusercontent.com/47288302/57821130-61eb8680-775d-11e9-9253-c14902ce55b7.JPG)

**Register and Create Profile:**  
To use this feature, the person must create an account to be a registered user. Then the users should be able to create and edit their own profile 

**Ask questions:** 
The user will be able to create questions, view the questions and edit the questions

**Answer a question:**  
The user once logged in can answer a question, edit and delete it.  

**Answer Notifications:** 
Once a question is answered, the user will be notified the question is notified via database. The count of the notifications depends on the number of answers. 
![features](https://user-images.githubusercontent.com/47288302/57821264-e3dbaf80-775d-11e9-899a-f3a806b55a1b.JPG)

**Unit Testing 9 successful tests and 9 asserstions.**
![unitTestingSS](https://user-images.githubusercontent.com/47288302/57821347-33ba7680-775e-11e9-8afc-43c1cd1650a9.JPG)

**Link to Heroku Application**
 This appliction will work until when the user account is created and then heroku website is showing a database error 
 Link to heroku app: https://is601faqmp3.herokuapp.com
 
 **Website for working Demo Video**
 Link to demo video on youtube:https://youtu.be/ElwqQTunbvE

**References**
The Instruction videos provided by Prof. Keith Williams at NJIT are useful for those who want to start the career in Web development field.  Link to Mr. Keith Williams Youtube Channel : https://www.youtube.com/channel/UCSOm2zK1tPb3DyUqYR36Xag

**License**
Faq is MIT license
