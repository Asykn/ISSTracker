ISS Tracker
=============

:Author: Nurul Asyikin Mat Zaid <nurulasyikinzaid@gmail.com>

Introduction
~~~~~~~~~~~~

ISS Tracker is to track the position of the ISS on current or past

dates and times. The location will be plotted on the map to show 
the 
position of the ISS at a certain date and time.



Note that the time is in GMT time zone format. 


Installation
~~~~~~~~~~~~

>>> Python 3.10.1
>>> Turtle
>>> Request
>>> Webbrowser
>>> geocoder
>>> datetime


Example & Usage
~~~~~~~~~~~~~~~

>>> Run the code on any editor

>>> Run python file of isslocation.py

>>> Enter date YYYY-MM-DD

>>> time HH:MM 



Note that time is running on the GMT timezone, although it is more 

complicated than working in UTC as you need to use the 'normalize'

method to handle daylight savings time
and other timezone transitions.


Problems with ISS past time and Localtime
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

The major problem we have to deal with is that we cannot get 
the passing time 
of the ISS location. The time that the 
user can enter in GMT timezone instead 
of in UTC.


Where was the International Space Station (ISS)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

The ISS orbits 400 km above the Earth at approximately 29,000 km/h. 
It is the third brightest object in our sky, making it possible to 
catch a glimpse of the ISS from ground level.


API
~~~

>>> iss get_pass
>>> open notify


Issues & Limitations
~~~~~~~~~~~~~~~~~~~~

- ISS location is in real-time, and the longitude and latitude will be
  
shown at the terminal every 10 seconds. 



- Timezone is in GMT format.


Further Reading
~~~~~~~~~~~~~~~

More info than you want to know about ISS Location:
https://www.nasa.gov


Contact
~~~~~~~

Nurul Asyikin Mat Zaid <nurulasyikinzaid@gmail.com>