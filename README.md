# SEC digital calendar and lectionary

* Version: 3.3.0
* Last updated: Tuesday 28 November 2017


<!-- MarkdownTOC -->

- [1. About](#1-about)
    - [Readings](#readings)
    - [Translations](#translations)
    - [Accuracy](#accuracy)
    - [Sources](#sources)
- [2. Style guide](#2-style-guide)
    - [Key](#key)
    - [Sundays](#sundays)
    - [Weekdays](#weekdays)
    - [Feast days](#feast-days)
    - [Reading style](#reading-style)
        - [Notes](#notes)
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


### Key

* `{Optional}` : This information is optional.
* `|`          : Or, the information after this is an alternative.


### Sundays

```
Week of Season | Week of Proper 45
First Sunday of Season [1|2] Colour | Second Sunday after Season [3] Green
SPB Third Sunday after Season | SPB Season 3
(Ordination of the Rt Revd Surname, Bishop of Diocese, 2017)

EUCHARIST{: Continuous}
OT
Psalm
NT
Gospel

{EUCHARIST: Thematic
OT
Psalm
NT
Gospel}

DAILY PRAYER: Week X | Season
OT
NT
Gospel

[MORNING PRAYER: Season
OT
NT

EVENING PRAYER: Season
OT
NT]

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

The order of information at the start of weekdays is as follows:

1. Week of season, e.g. `Week of Proper 9 (if after Pentecost)`.
2. Saint's day, e.g. `John XXIII, Bishop of Rome, Reformer, 1963 [6] White`.
3. Day after Sunday, e.g. `Monday after Pentecost 2, Green`.
4. Whether the day is a `Rogation Day` or `Ember Day`.
5. Ordination of a bishop (in parentheses).

```
Week of Season 1 | The days following Season | etc.
Name, Priest, 1916 [6] Colour | Festival [1] Colour
Thursday after First Sunday of Season, Colour
7 January
[Rogation Day | Ember Day]
(Ordination of the Rt Revd Name, Bishop of Diocese, 2017)

DAILY EUCHARIST
NT
Psalm
Gospel

DAILY PRAYER: Week X | Season
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
Andrew, Apostle, Patron of Scotland [4] Red
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

In this style guide I have changed a few of the conventions used in the SEC Calendar and Lectionary to reference Bible passages. This is to improve clarity.

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

#### Notes

* There must be no space before or after a colon (`:`). Colons are used to distinguish chapter (left of the colon) from verses (right of the colon).
* There must always be a space after a comma (`,`) or semicolon (`;`).
* There must be no space within a range (e.g. `1:1-10`) unless the range spans more than one chapter (e.g. `1:1 - 2:10`) in which case there must be a space either side of the dash to aid readability.
* Dashes must be simple dashes (`-`), not an en dash `–` or em dash `–`.




---

## 3. Other editions

### Church of England edition

See Fr Simon Rundell's [Electronic Ordo](http://www.frsimon.uk/electric-ordo-calendar/) containing daily information and readings for Mass each day according to both the Anglican (Common Worship) or Roman lectionaries.


### Roman Catholic editions

See [Catholic Apptitude](https://catholicapptitude.org/apps/catholic-calendar-apps/) for a number of similar calendar and lectionary resources.