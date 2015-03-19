# Conky
Conky Config with Icons
========================
Screenshot:

![Conky](https://raw.github.com/StephenEibert/Conky/master/conkyscreen.jpg)

Installation
------------
You will need to first get conky and lm-sensors for temperature readouts

``
$ sudo apt-get install conky lm-sensors
``

Fetch the config file with fonts and icons from GitHub repo

``
$ git clone git://github.com/StephenEibert/Conky.git ~/.conky
``

Link:

``
ln -s /.conky/.conkyrc ~/.conkyrc
``

Features
--------
* System Information
* CPU, RAM, and Disk Graphs
* CPU, GPU and Mobo Temperatures
* Processes
* Date and Time
* HDD Graph
* Network Graph and Information
