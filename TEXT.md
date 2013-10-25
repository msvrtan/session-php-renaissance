
****
Pozdrav svima,

Sjecate se ovoga 'old school' php koda? Spoji se na bazu, izvuci ID direktno iz requesta, pa malo HTMLa, pa eto zaboravili smo jos nesto dohvatiti iz baze pa smo tu ubacili kod malo unutra. 

**
Hvala bogu da su ta vremena iza nas, odrzivost onakvoga koda je ufff. Sa OO i MVC patternima kod moze izgledati puno ljepse, odvojeno po namespacovima..

**
Razdvojeni prikaz od biznis logike

**
A podrzava i nasljedjivanje kako bi olaksao rad

****

Da, PHP doživljava renesansu! 

****

Moje ime je Miro Svrtan, PHPom se bavim vec 14-15 godina a trenutno sam zaposlen kao tehnicki analiticar u Njuskalu,a u slobodno vrijeme sam jedan od organizatora ZgPHP Meetupa i WebCampa.


****

PHP je poceo 1995, ali je tek sa PHP 3 1998 poceo dobivati na vecoj popularnosti. Nazalost verzija 4 je napravila vise stete nego koristi sa svojim wannabee OO paradigmom ali od 2004 sa PHPom 5 stvari su se pocistile. Ovdje navedene minor verzije su donjele velike promjene u jeziku, ali zbog stigme toga da PHP 6 donosi unicode support su pustene kao .3/.4/.5 umjesto promjene verzije.

**

Sjecate se onoga jezika koji nam je godinama zadavao muke dok smo micali stvari po ekranu, skrivali ili pokazivali ih? OK znali smo ga koristiti i za AJAX pozive :) U zadnjih par godina je dozivio revoluciju, daleko vecu od PHPa ali je to prirodno jer neovisno o odabiru server-side language svi smo ga koristili u nekome dijelu svoga zivota.


**

Sad ja imam nekoliko pitanja za vas..

Koliko vas je koristilo PHP prije pa ste presli na neki drugi jezik?
Koliko od vas je koristilo cisti vanilla php?
Neki od inhouse ili vlastitih frameworka/librarya?
A neki od fw-a iz zajednice?

****

Konkurencija, neki imaju odredeni headstart nad PHPom. Dosli su kasnije a cesto zbog postojanja prakticki jednoga frameworka uspjeli su usredotociti se na isti.

**

PHP, ako pitate developere koji je najbolji framework, na njih 10 cete dobiti 11 komada :) Ovdje su neki od najpopularnijih u zadnjih 4-5 godina, abecednim su redom poslagani da me moja zajednica neubije kako je to A bolji od B :) 

**
Nazalost izvuci neku 100% vjerodostojnu statistiku je nemoguce, cisto sam ovdje naveo par statistika da vidite raznolikost.

** 
Usporedbe. Developeri vole usporedjivati X i Y, cesto imam priliku naletiti na usporedbe PHPa sa Djangom i RoRom .. Da Django je bolji .. RoR isto tako... ali usporedujemo krive stvari ... PHP je jezik ovo su frameworci. PHP developeri vole napraviti svoj framework, onaj koji je puno bolji od svih ostalih, znas ono ovaj to radi krivo ja cu to bolje. Naravno da u tome neuspiju jer community driven projekti sa godinama razvoja, desecima-stotinama-tisucama developera te tisucama razlicitih projekata napravljenih na njima - nemoguce im je konkurirati. 

I sve vas molim da prestanete sa glupim usporedbama ...

**
Pro's & con's: 

** 

Con #1: legacy kod. Evo jedan projekt po kojem sam morao neke sitnice mjenjati prije 2 godine. Iako godinama vec zivim u totalno drugacijem PHP svijetu shvatio sam brzo zasto je dosta ljudi pobijeglo ... ubij me za ovo .. ali ovaj kod se poceo raditi prije 13 godina, nazalost nitko jos nije nasao zelju/volju/vremena refaktorizirati kod i napraviti nesto od njega.

Da nazalost ovakve stvari rade velike probleme u zajednici .. 10 godina star kod, pisan totalno drugacijom paradigmom koja se vise prakticki ne koristi ... ali eto projekt je aktivan jer ga jako puno ljudi koristi


** 
Con #2: lak pocetak .. jako puno pocetnika krene kuckati kod iz nule i vrlo brzo sebe ili projekt upuca u nogu ... u drugim jezicima pocetnici krecu odmah sa koristenjem nekoga fw-a i izbjegavaju mogucnost da naprave toliku kolicinu gresaka i losega koda... vecina pocetnika pocne u PHPu sa kodom sa prvoga slajda :(



**
Con #3: nekonzistentnost ... core PHPa godinama nije imao naming scheme, specifikaciju, RFCove i sl vec je svatko radio .. to se promjenilo ali eto ostale su neke stare metode sa glupostima ... koliko me zna zivcirati davno sam se pomirio da dobar IDE rjesava ovakve stvari .. 


** 
Pro #1: manual ... php.net ima jako dobru dokumentaciju sa objasnjenjem i primjerima ... 15 godina rada zajednice na tome puno znaci ... nekada mozete vidjeti primjere kako nesto napraviti iz 2002 i bas pokrivaju slucaj koji vama treba ...

** 

Pro #2: lagani pocetak .. da lako je poceti je i plus a postojanje velike kolicine razlicitoga a cesto i jeftinoga hostinga puno znaci na pocetku ... 

**
Pro #3: evolucija .. kao jezik i zajednica u godinama, sve se radi kao evolucija ne revolucija .. ideja nije potrgati sve sto je do sada radjeno a sa druge strane stvari se ipak mijenjaju ... jezik dosta napreduje, projekti su aktivni, na librarijima i frameworcima radi sve vise i vise ljudi zajedno a zajednica nikad nije bila ovako zivahna i motivirana biti bolji

** 
Pro #4: zajednica .. jako veliki broj developera, ogroman broj konferencija po cijelome svijetu sa puno predavaca koji dolaze sa razlicitih kontinenata ..  u Zagrebu se odrzavaju redovna mjesecna druzenja a ove godine smo imali i prvu konferenciju, dosta predavaca i publike je bilo izvan zagreba i hrvatske






1. Slide



Old school PHP. Probably many of you remember PHP code looking something like this. Header will connect to DB and get some data, then a bit of HTML and everything you forgot or depends on some ifs written down. And of course no escaping of get params when database querying is done.

Well now you can also write it little bit nicer, having classes in namespaces and separating logic from display. If you really want to :) Twig templating was inspired by Jinja and Django Templating engine, lot of you from python world will see this is familiar bit.

Yes PHP is having a renaissance. My name is Miro Svrtan and if interested you can find me on twitter. A little bit about me. I'm working with PHP since last century, currently I'm emplpyed as techincal analyst at Njuskalo. In my spare time I try to organize stuff for community, I'm one of organizers of ZgPHP meetup group and WebCamp conference.

* Milestones

With PHP4 some kind of idea of object orientation was given but till PHP 5 this was well, lets not talk about it. With 5.3 the major changes started to happen: namespace, late static binding, closures, php archive, improved garbage collection.

* Javascript

Lets get back on track. Similar to Javascript, you remember that language that we all used to move stuff around web browser screen? Well somehow people started to use it for something more then just showing/hiding stuff and it had a great impact on web world in general. Similar to this but at smaller scale (since Javascript has and is used independently of your server-side language of choice) PHP is having a renaissance.

* Vox populi

How many of you here have programmer in PHP but have switced to some other server-side language? Keep your hands up please. How many used vanilla PHP only? How many used some inhouse fw? How many used some opensource fw?

Some of you might have used it long time ago, when there were no classes, namespaces, MVC frameworks (some of you might be still using it that way :)) or maybe few years ago when there were number of new frameworks, every month there was a new flavour.  When looking into my community, lot of companies are still using some inhouse framework but that is starting to change. Why? In last few years came strong and opensource frameworks to life.



* Competition

"Newer" web languages are having a headstart on us since they are mostly based around one framework. Even to a point that people are confused where one R ends and another starts. There are more then few devs writing/provoking comparison of PHP to Django/RoR. Not PHP to Pyhton or Ruby. Yes those frameworks are much better then PHP. A lot better. Incredibly better. In PHP you would be forced to programme all that magic that comes bundled with those frameworks. And you would have to be much smarter then hundreds/thousands of devs that spent their time thru years in making that framework better.


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



