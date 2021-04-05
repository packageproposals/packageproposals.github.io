---
layout: post
title: The top five must have libraries for every Laravel project.
date: 2021-04-01
summary: |
 Here are the packages you need for most projects.
tags: php laravel symfony
categories:
  - php
  - laravel
---
**The top five must have libraries for every Laravel project.**

**Laravel Activity log by spatie.**

You will need this package in your project to handle activity logs of all eloquent model . This package does all the logging behind the hood.

[Github Link]( https://github.com/spatie/laravel-activitylog)

**Laravel   Tinker**

This tool will help you to run extra code even when the app is already shipped in production . you can be able to perform all eloquent queries via the terminal. for example You can list all uses using ```App\User::all()```

To access tinker you have to enter this artisan command in your terminal/shell/cmd etc .
```php  artisan tinker```
[Github Link ](https://github.com/laravel/tinker)

Tinker is a command-line interface that is available with a Laravel and Lumen. Tinker is a command tool that works with a php artisan.

**Laravel   passport.**

Laravel ships with a strong and robust authentication engine , Laravel passport takes out the pain in setting up user authentication and authorization.
*Laravel Passport* provides a full OAuth2 server implementation for your Laravel application in a matter of minutes
[Github link ](https://github.com/laravel/passport) , it should be noted that if  you are building an SPA then you might need to use Laravel Sanctum.

**JWT   AUTH.**
If you are building an API or micro services,then you are going to need to handle authentication of users via access tokens, This is so far the best package for issuing,refreshing and destroying tokens and managing user state. It is embedded together with the elegant and exquisite Laravel Auth.
[Github Link](https://github.com/tymondesigns/jwt-auth)

INETIAJS
JavaScript is the king of web without a doubt , this is evidenced by the stack overflow developer surveys of the last 5 years.For a modern monolithic app, using the ever powerful Javascript is not choice  ,inertia Js has positioned it self is the  best option available to remain monolith as well using the best of frontend frameworks such as React, Vue and Angular , you can easily interact with collection of any model with an inertia Js controller.
[Github Link](https://github.com/inertiajs/inertia-laravel) 