# Austria (Österreich) - Österr. Bundesliga, Zweite Liga, ÖFB Cup


## What's `football.db`?

A free open public domain football database & schema
for use in any (programming) language (e.g. uses plain text data sets).
More [`football.db` Project Site »](http://openfootball.github.io)

## Intro

Free open public domain football data for Austria (Österreich).
National football club leagues and cup tournaments include:

| Level |                                  |               |
| ----- | -------------------------------- | ------------- |
| I     |  Österr. Bundesliga¹             |  12 Clubs     |
| II    |  Erste Liga (2. Liga)            |  16 Clubs     |
| III   |  Regionalliga Ost, Mitte, West   |  3 x 16 Clubs |
|       |
| Cup   |  ÖFB (Austrian) Cup |


¹: Regular Season, Championship Round + Relegation Round


Before 2018/19

| Level |                                  |               |
| ----- | -------------------------------- | ------------- |
| I     |  Österr. Bundesliga              |  10 Clubs     |
| II    |  Zweite Liga (2. Liga)           |  10 Clubs     |


Example:

```
= Österr. Bundesliga

1. Runde

[Sa 19.7.]
  16.30   RB Salzburg       6:1 (2:0)  Rapid Wien
            [Ulmer 30' Alan 40' Mané 69' Soriano 77', 79' Kampl 84'; Hofmann 90+2' (Elf.)]
  19.00   SV Ried           3:1 (1:0)  Wr. Neustadt
            [Walch 4' Möschl 69' Pichler 82'; Kainz 66']
  19.00   Admira Wacker     1:4 (1-1)  Wolfsberger AC
            [Schicker 45+2' (Elf.); Žulj 36' Trdina 63' Wernitznig 74', 78']
  19.00   SCR Altach        1:0 (0:0)  Sturm Graz
            [Roth 68']
[So 20.7.]
  16.30   Austria Wien      1:1 (0:0)  SV Grödig
            [Kamara 90+3'; Schütz 54']

...
```

```
= Austria Wien

13  Heinz Lindner               GK  2009-
31  Osman Hadzikić (BIH)        GK  2014-
77  Tino Casali                 GK  2014-

 4  Vanče Šikov (MKD)           DF  2014-
 5  Philipp Koblischek          DF  2014-
 8  Jens Stryger Larsen (DEN)   DF  2014-
14  Manuel Ortlechner           DF  2009-
15  Christian Ramsebner         DF  2013-
18  Sebastian Wimmer            DF  2014-
29  Markus Suttner              DF  2008-
30  Fabian Koch                 DF  2011-

 6  Mario Leitgeb               MF  2014-
 7  Marco Meilinger             MF  2014-
10  Alexander Grünwald          MF  2011-
17  Florian Mader               MF  2010-
20  Alexander Gorgon            MF  2010-
21  Sascha Horvath              MF  2013-
22  Bernhard Luxbacher          MF  2013-
23  David de Paula (ESP)        MF  2014-
25  James Holland (AUS)         MF  2012-
28  Daniel Royer                MF  2013-
34  Peter Michorl               MF  2014-
35  Thomas Salamon              MF  2014-

 9  Martin Harrer               FW  2014-
11  Ola Kamara (NOR)            FW  2014-
24  Roman Kienast               FW  2012-
```


## Build Your Own `austria.db` Copy

Use the `sportdb` command line tool to build your own `austria.db` copy
from the plain text data sets. [More »](https://github.com/openfootball/datafile)


### Alternative I - Use the Quick Starter Templates

Use the quick starter datafile templates to start from scratch. Examples:

Build the database for all Austrian clubs, leagues and seasons:

    $ sportdb new at

Build the database for the 2020/21 season:

    $ sportdb new at2020-21

[More »](https://github.com/openfootball/quick-starter)



### Alternative II - Do-It-Yourself (DIY) - Downlad and Unpack Zip Archive or Git Clone

Download and unpack the zip archive with the datasets or if you have git installed use the `git clone` command to
get a local copy.

Try in your working folder (that is, `/austria`):

```
$ sportdb build
$ sportdb --verbose build     # or for more (verbose) details incl. debug info
```

This will

- setup a new single-file SQLite database e.g. `./sport.db` and
- read in all datasets in plain text (`.txt`)

That's it.




## Questions? Comments?

Send them along to the
[Open Sports & Friends Forum/Mailing List](http://groups.google.com/group/opensport).
Thanks!
