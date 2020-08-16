# HANGMAN

Data Analytics, August 2020, Berlin
Imogen Rickert

## Content
- [Game Description](#game-description)
- [Rules](#rules)
- [Workflow](#workflow)
- [Organisation](#organisation)

## Game Description
I created a hangman game where the user has to guess a country chosen by the computer. 

## Rules
The computer randomly selects a country. The user has to try to guess the country, one letter at a time. 

When the user correctly guesses a letter, s/he has the chance to guess the whole word if s/he would like to. 

The user has 6 guesses in total. If s/he cannot guess the country correctly in 6 or less guesses, s/he loses the game. 


## Workflow
First I chose a category of words from which the computer can randomly choose from (countries).

Then I broke up the work into multiple smaller blocks to be able to test the code regularly and quickly fix bugs. 

Next, I combined them in the 'game()' function and finally, I wrote the 'intro()' function as an additional introduction to explain the rules at the start. 


## Organisation
I used Jupyter Notebook to write the code.
My repository consists of  two files: jupyter notebook and a readme file.
