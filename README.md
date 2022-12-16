## laravel 8 chat application

### Requirement as below:
- Please see coding challenge below,
Coding Challenge
Design a messaging system using Laravel 8. The system should be able to view, send, receive, and delete messages between various users. Restrictions on this you should use tailwind css for any css styling. Use blade templates and partials to their full effect. Also follow DRY and KISS principles.
 Deliverables:
Git repo including instructions on how to install and run the application in a README file.

### Follow installation steps:

Fire commands in terminal : 
#####  Step : 1

```
git clone https://github.com/Asad9299/chat-demo.git
```
##### Step : 2

```
cd  chat-demo
```
##### Step 3

```
cp .env.example .env
```
Create db on your system and update database details in .env file
##### Step : 4

```
composer install
npm update
```

##### Step : 5
```
php artisan migrate
```
- This will generate tables in db and some random dummy users to check app.
- You can use any email to login from users table.
- All user's password is "12345678".
