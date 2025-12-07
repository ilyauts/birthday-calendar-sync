# birthday-calendar-sync
Automatically sync friends and family birthdays with your Google Calendar

## Motivation
In the late 2000's and early 2010s, Facebook was the one stop shop for keeping tabs of your friends' birthdays.

Many users have since left Facebook, however, leaving you unaware of their birthdays. 

This repo features a collection of scripts and examples for easily managing birthdays and names and relationships between various people!

## How to Run
1) Clone this spreadsheet: https://docs.google.com/spreadsheets/d/10HSlh794jFTi01ks-DnEoY5FaY5GzWb2PyLuEw2lqpA/edit?usp=sharing
2) Update Spreadsheet with the names and birthdays of your friends and family 
3) Click Extensions --> App Script
4) Paste the contents of the app.gs file
5) Replace the contents of the `SPREADSHEET_ID` variable with the hash found in the url of your cloned spreadsheet!
6) From the dropdown in the toolbar, select `mainUpdate`
7) Click `Run`
