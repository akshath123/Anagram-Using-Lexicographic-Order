# Anagram Using Lexicographic Order

## Introduction
This application is developed for finding the Anagram for a given word. There is a GUI for the application which makes the it easy for the user to use the application. The term anagram means that a word, phrase, or name formed by rearranging the letters of another, such as spar, formed from rasp, eg: tea anagram is eat. Lexicographic order when applied to permutation it finds the next highest order permutation, more in detail explanation can be found [here](http://mathworld.wolfram.com/LexicographicOrder.html). 

## Motivation behind the project
This project was built in 3rd semester as a project for the subject Discreate Mathematics as part of my curriculum. 

## How was it done?
I labeled each word with a number from 1 to N ( where N represents the length of the word ). Next using Lexicographic ordering I found the next highest order permutation using indexing and swaped the letters accordingly giving a new word. With the new word I checked the whether the word is meaningful or not using a database. If it is a meaningful word I am presenting it to the user. 

## To see the demo of it click here 

### Note: Make sure you add the mysql-connector in the project when using the application
