csv2mysql
=========

A quick and dirty script for creating a mysql table from a csv file. 
A header row is required for the csv, and can be optionally used to create the 
table column names.

All variables can be a) set in the script explicity or by extending it b) set in an
external file named config.php in the same folder as this script, c) in a php
file referenced as the first argument on the command line. If there is a
second command line argument, it is the csv file to be parsed.



