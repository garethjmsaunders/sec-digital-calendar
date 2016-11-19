# SEC digital calendar and lectionary

* Version: 3.2
* Last updated: Saturday 19 November 2016


<!-- MarkdownTOC -->

- [1. About](#1-about)
    - [Readings](#readings)
    - [Translations](#translations)
    - [Accuracy](#accuracy)
    - [Sources](#sources)
- [2. Style guide](#2-style-guide)
    - [Sundays](#sundays)
    - [Weekdays](#weekdays)
    - [Feast days](#feast-days)
    - [Reading style](#reading-style)
- [3. Other editions](#3-other-editions)
    - [Church of England edition](#church-of-england-edition)
    - [Roman Catholic editions](#roman-catholic-editions)

<!-- /MarkdownTOC -->


---

## 1. About

This repository contains the source files for the SEC digital calendar project hosted at <http://www.seccalendar.co.uk>.

These files allow you to import or subscribe to the [Scottish Episcopal Church](http://www.scotland.anglican.org/) calendar (saints’ days, festivals and readings) using Microsoft Office Outlook Calendar, Google Calendar, or any other compatible calendar application.

The files were originally produced for my own personal use, so they may not have all the details that you want in them.

Feel free to adapt these files for your own use, subject to your agreement of the [license](https://github.com/garethjmsaunders/sec-digital-calendar/blob/master/LICENSE).


### Readings

The readings for category 4 saints days and lesser festivals are simply those for that day of the week in relation to the previous Sunday rather than specifically for that minor saint/festival. For example, the readings given for Ambrose of Milan (Friday 7 December) are those for the Friday of Advent 1.

In other words, I've used only readings from The Lectionary and the Readings for Festivals, and not those from elsewhere or from the Readings for Special Occasions or Common Readings for Saints Days.


### Translations

Where possible I have always translated the festival of a saint, if it coincides with a higher-category feast, to the next available date. It is possible that a suitable, nearby date has not been found and so that feast day has been omited for this year.


### Accuracy

While every effort has been made to ensure that the data contained in these files is correct and up-to-date, occasionally mistakes do get made and errors slip into the final production files.

The Revd Gareth J M Saunders will not be held accountable for any issues that arise from the use of these files. You use them entirely at your own risk.

To report any errors please email Gareth J M Saunders.


### Sources

[Calendar and Lectionary source materials](http://www.scotland.anglican.org/who-we-are/publications/liturgies/calendar-and-lectionary/) may be downloaded for free from the Scottish Episcopal Church website.

The Guide to the Calendar and Lectionary is an annual publication that offers guidance on how to use the lectionary each church year, especially in relation to translated (moved) festivals.

Material from the Revised Common Lectionary copyright © 1992 by the Consultation on Common Texts.




---


## 2. Style guide

The following style guide is use when compiling the documents.

Note that Outlook 2007+ for some obscure reason changes uppercase words to a blue-formatted heading. 


### Sundays

```
Week of Proper 45
FIRST SUNDAY OF SEASON [1|2] Colour | Second Sunday after Season [3] Green
[SPB Third Sunday after Season]
(Ordination of the Rt Revd Name, Bishop of Diocese, 2016)

EUCHARIST

{Continuous: | Service:}
OT
Psalm
NT
Gospel

[
{Thematic: | Service:}
OT
Psalm
NT
Gospel
]

DAILY PRAYER: {Week | Season}
OT
NT
Gospel

[ or
MORNING PRAYER: Season
OT
NT

EVENING PRAYER: Season
OT
NT
]

ALTERNATIVE PSALMS
Morning: Psalm
Evening: Psalm

---

SPECIAL SUNDAY

EUCHARIST
OT
Psalm
NT
Gospel
```


### Weekdays

```
Week of Season 1 | The days following Season | etc.
Name, Priest, 1916 [6] White | FESTIVAL [1] White
Thursday after First Sunday of Season
7 January
[Rogation Day | Ember Day]
(Ordination of the Rt Revd Name, Bishop of Diocese, 2016)

DAILY EUCHARIST (Colour)
NT
Psalm
Gospel

DAILY PRAYER: {Week | Season}
OT
NT
Gospel

[ or 
MORNING PRAYER: Season
OT
NT

Evening before FESTIVAL (4 Month)

EVENING PRAYER: Season
OT
NT
]

[
ROGATION | EMBER DAY READINGS
OT
Psalm
NT
Gospel
]
```


### Feast days

```
Week of Advent 1
Andrew,Apostle, Patron of Scotland [4] Red
30 November

EUCHARIST
OT
Psalm
[NT]
Gospel

MORNING PRAYER: Festivals
OT
NT
Gospel

EVENING PRAYER: Festivals
OT
NT
Gospel

---

Week of Advent 1
Thursday after First Sunday of Advent
30 November

DAILY EUCHARIST (Violet)
OT
Psalm
Gospel

DAILY PRAYER: Anticipation
OT
NT
Gospel

ALTERNATIVE PSALMS
Morning: Psalm 1 | Psalms 1 and 3 | {options below}
Evening: Psalm 2
```




---

### Reading style

In this style guide I have changed a few of the conventions used in the SEC Calendar and Lectionary to reference Bible passages. This is in the interest of improved clarity.

Reading ranges MUST be laid out in the following formats:

```
Reading 1:1-10
Reading 1:1-10, 15-20
Reading 1:1, 15-20
Reading 1:1-10, (15-20)
Reading 1:(1), 15-20
Reading 1:(1-10), 15-20
Reading 1:1 - 2:10
Reading 1:1-5; 2:1-10
Reading 1:1-5 or Reading 2:1-10, 15-20
```




---

## 3. Other editions

### Church of England edition

See Fr Simon Rundell's [Electronic Ordo](https://frsimon.wordpress.com/electric-ordo/) containing daily information and readings for Mass each day according to both the Anglican (Common Worship) or Roman lectionaries.


### Roman Catholic editions

See [Catholic Apptitude](https://catholicapptitude.org/apps/catholic-calendar-apps/) for a number of similar calendar and lectionary resources.