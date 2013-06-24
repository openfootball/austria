# Austria (Österreich)

## What's `football.db`?

A free open public domain football (soccer) database & schema
for use in any (programming) language
(e.g. uses plain text fixtures/data sets).
More [`football.db` Project Site »](http://openfootball.github.io)

## Intro

Free open public domain football data for Austria (Österreich) / Europe. Events include:

- Österr. Bundesliga
- Erste Liga (1. Liga)
- Regionalliga Ost/Mitte/West
- ÖFB Cup

Example:

~~~
### Bundesliga Teams

austria,     FK Austria Wien|Austria Wien,                   FAK,  city:wien
salzburg,    FC RB Salzburg|RB Salzburg|Red Bull Salzburg,   RBS,  city:salzburg
...
~~~

~~~
### Bundesliga 2013/14

1. Runde  //  Sa+So 20.+21. Jul 2013

Sa, 20.07.2013 16.30  Austria Wien         FC Admira Wacker
Sa, 20.07.2013 19.00  SC Wiener Neustadt   RB Salzburg
...
~~~


## Command Line Tool - Build Your Own `football.db` Copy

To build your own `football.db` copy from the plain text fixtures
use the sportdb command line tool. Example:

Step 1:  Get a copy of the `world.db` fixtures

    $ git clone git://github.com/geraldb/world.db.git

Step 2:  Get a copy the `at-austria` fixtures

    $ git clone git://github.com/openfootball/at-austria.git

Step 3:  Let's build the `football.db`

    $ sportdb setup --include ./at-austria --worldinclude ./world.db

That's it. For more see the [`sportdb` command line tool project](https://github.com/geraldb/sport.db.ruby)
for more.



## Links

### Web Admin App

Try the `football.db` Web Admin app running on Heroku
[`footballdb.herokuapp.com/at`](http://footballdb.herokuapp.com/at).

### Österreichische Bundesliga

Official Site -> [`bundesliga.at`](http://bundesliga.at)

- Teams: 10
- Matches: 180 (=36 Rounds x 5 Matches)
- Rounds: 36 (each 5 Matches)

### Wikipedia

- [Österreichische_Fußballmeisterschaft_2013/14](http://de.wikipedia.org/wiki/Österreichische_Fußballmeisterschaft_2013/14)
- [Österreichische_Fußballmeisterschaft_2012/13](http://de.wikipedia.org/wiki/Österreichische_Fußballmeisterschaft_2012/13)

### Sport Newspapers

- Sport Woche (1x week)
- Sport Zeitung (1x week)



## Questions? Comments?

Send them along to the
[Open Sports & Friends Forum/Mailing List](http://groups.google.com/group/opensport).
Thanks!