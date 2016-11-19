# SEC digital calendar and lectionary

* Version: 3.1
* Last updated: Friday 14 October 2016


<!-- MarkdownTOC -->

- [1. About](#1-about)
    - [Readings](#readings)
    - [Translations](#translations)
    - [Accuracy](#accuracy)
    - [Sources](#sources)
- [2. Style guide](#2-style-guide)
    - [Format of description field](#format-of-description-field)
        - [Weekdays](#weekdays)
        - [Sundays](#sundays)
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


### Format of description field

Note that Outlook 2007+ changes uppercase to a blue-formatted heading.

#### Weekdays

```
[DAY]
Seraphim of Sarov, 1833 [6] White
Thursday after the First Sunday after Christmas
2 January
```

or

```
Wednesday after Pentecost 6
Week of Proper 14 [3] Green
```


#### Sundays

```
[SUNDAY]
Remembrance Sunday
Pentecost 22 [3] Green; SPB Trinity 21
Week of Proper 32
Date

[DAILY] EUCHARIST (Green)

Continuous: | Thematic: | Feast day-specific:

OT
Psalm
[NT]
Gospel

{DAILY | MORNING} PRAYER: {Week A | Season}
[Morning:]
OT
NT
Gospel

[EVENING PRAYER: {Week A | Season}]
OT
NT
Gospel

ALTERNATIVE PSALMS
Morning: Psalm 1 | Psalms 1 and 3 | {options below}
Evening: Psalm 2
```


#### Feast days

```
Week of Advent 1
Andrew,Apostle, Patron of Scotland [4] Red
Date

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
Wednesday after First Sunday of Advent
Date

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