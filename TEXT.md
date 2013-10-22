
1. Slide



Old school PHP. Probably many of you remember PHP code looking something like this. Header will connect to DB and get some data, then a bit of HTML and everything you forgot or depends on some ifs written down. And of course no escaping of get params when database querying is done.

Well now you can also write it little bit nicer, having classes in namespaces and separating logic from display. If you really want to :) Twig templating was inspired by Jinja and Django Templating engine, lot of you from python world will see this is familiar bit.

Yes PHP is having a renaissance. My name is Miro Svrtan and if interested you can find me on twitter. A little bit about me. I'm working with PHP since last century, currently I'm emplpyed as techincal analyst at Njuskalo. In my spare time I try to organize stuff for community, I'm one of organizers of ZgPHP meetup group and WebCamp conference.

Lets get back on track. Similar to Javascript, you remember that language that we all used to move stuff around web browser screen? Well somehow people started to use it for something more then just showing/hiding stuff and it had a great impact on web world in general. Similar to this but at smaller scale (since Javascript has and is used independently of your server-side language of choice) PHP is having a renaissance.

Some of you might have used it long time ago, when there were no classes, namespaces, MVC frameworks (some of you might be still using it that way :)) or maybe few years ago when there were number of new frameworks, every month there was a new flavour.  When looking into my community, lot of companies are still using some inhouse framework but that is starting to change. Why? In last few years came strong and opensource frameworks to life.

"Newer" web languages are having a headstart on us since they are mostly based around one framework. Even to a point that people are confused where one R ends and another starts. There are more then few devs writing/provoking comparison of PHP to Django/RoR. Not PHP to Pyhton or Ruby. Yes those frameworks are much better then PHP. A lot better. Incredibly better. In PHP you would be forced to programme all that magic that comes bundled with those frameworks. And you would have to be much smarter then hundreds/thousands of devs that spent their time thru years in making that framework better.

How many of you here have programmer in PHP but have switced to some other server-side language? Keep your hands up please. How many used vanilla PHP only? How many used some inhouse fw? How many used some opensource fw?

This is one of main problems in PHP community now. Lot of projects are more then 10 years old, most of opensource projects are not using fw but they built it from scratch.

One of best examples is Mantis bug tracker. I had to modify it a bit 2 years ago and was pissed off. 
 - https://github.com/mantisbt/mantisbt/blob/master/bug_update_page.php
As you can see first commit was in 2000
 - https://github.com/mantisbt/mantisbt/commits/master?page=217
 - https://github.com/mantisbt/mantisbt/commit/91417fa8908afab2554be800ed82aaf5194cdd0b

A lot of us are still battling with some applications that are having so old legacy code that objects were not invented yet. This is headstart that other languages have on us.

But there comes a new breed of PHP....

- clean and modular, OO and MVC frameworks
- standardized coding format
- package manager


* Composer - Package manager / Packagist - package repository

Brought to the community by Sf2 crowd, started in April 2012 and has 17k packages with 79mil installations. 
https://packagist.org/statistics


* Frameworks
Zend 2 - enterprisey one
Symfony 2 - the star :) , ispired by Django, RoR and Spring
Laravel 4- built using some components from Sf2, very similar in idea to RoR
Silex - microframework built with Sf2 components


* Coding: Framework Interoperability Group

There is unofficial, community organization trying to promote better integration of code from different projects together by suggesting coding standards,etc. Idea is not to have 75 different modules/libraries/bundles doing same thing, trying to use same coding standard ...

* PSR

One of the biggest accomplishments (also a very controversial one) is PSR coding standards. Should we use spaces or tabs, naming in camelCase, PascalCase or underscore_naming

* Better practices

- unit testing
- functional testing
- behavior testing


* PHAR

PHP archive format, similar to JAR, gives opportunity to pack whole application into one file for easier usage and distribution. Examples: composer, phpunit, codesniffer, PHP mess detector

* In the wild

- Github - most of PHP Open Source projects are hosted there 
- Travis CI 
- Vagrant



