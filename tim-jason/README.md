# Kilovolt blog

**Author**: Tim & Jason
**Version**: 5.0.1 (increment the patch/fix version number up if you make more commits past your first submission)

## Overview
This is a blog that takes JSON data (locally but simulating remotely), fetches and parses into the appropriate html fields

## Getting Started
 The user would fire the application and be able to change filters to focus on certain authors/categories, and on reload the data would not be fetched from the .JSON file but rather the local storage of that data 

## Architecture
 HTML, CSS, JS, JSON, AJAX. The page checks for rawData object and populates it if it exists, otherwise it takes the data from the .JSON file, stringifyies and parses into the functions

## Change Log

04-17-2018 9:10am - Answering comments, started building ‘else’ of fetchAll

04-17-2018 10:00am - Added function call to new.html, commented

04-17-2018 10:30am - a/c/p, switch drivers

04-17-2018 11:15am - Implemented local storage/stringify of JSON data

04-17-2018 11:40am - fixed article.loadAll to render local storage if there is any

## Credits and Collaborations
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Conditional_Operator
https://www.w3schools.com/jsref/prop_win_localstorage.asp
Javascript & jQuery by Jon Puckett