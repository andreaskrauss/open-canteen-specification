=========
The model
=========


Shops
=====

Shops represent any place where food is sold. 
It includes canteens, cafeterias, bistros, and more.
All of these have several attributes in common.
Therefore, a shop has following attributes:

ID,
Name,
Coordinates?
OpeningTimeRange
    OpeningTimes
        [{
            ID: 0-6 => Mo-Su
            times: [] (alternating times: [open. closed, open, closed])
            How to interprete if time is higher than smaller
        }]


Menus
=====

ID
DayOfTheWeek
Meals


Meals
=====

ID
Name
Ingredients
Price: [Price Group]


Price Groups
============

Companies:
    internal
    external
    special-offers

universities
    students
    employees
    guests
    default: either group or link to other price group




Database Models
===============

SQL Database
------------

NoSQL Database
--------------

