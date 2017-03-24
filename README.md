
# Exercises on Collections and Iteration

## What You Will Learn

This assignment will provide repetitious exercises in order to practice dealing with collections of different types and iterating over them.

## Prerequisites

* variables
* string interpolation
* conditionals/flow control
* basic understanding of collections/iteration
* readiness to look things up online!


## Submission
For each exercise, put your answers into a Ruby file (to be run and submitted). Feel free to work out the result first in `irb`.


## Exercise 0
###### Creating Arrays and Hashes

Save each of the following arrays and hashes into variables. You will use them throughout the assignment.

Eg. `fav_colours = ` ...

1. Create an array that contains the given information:
  * your favourite colours
  * the age of you and your siblings/cousins/friends
  * flip a coin 5 times and record whether or not the result was 'heads'
  * your three favourite performing artists
  * your favourite colours again (this time as symbols instead of strings)

1. Create a hash that contains the given information:
  * three words and their definitions
  * your favourite movie names and their year of creation
  * three cities of the world and their population
  * the names of your siblings/cousins/friends and their ages


## Exercise 1

1. Print out the array of coin flips.
1. Print out the first element of the array of your favourite colours.
1. Output the sorted version of the array of your friends and family members' ages.

1. Add a new baby (0 years old) to the array of your family's ages.
1. Using the hash of movie information, access and print the year of one of the movies.


## Exercise 2

1. Print out the last element of the array of your favourite colours.
  * Note: this should work for an array of any size!
1. Add a new city to the hash of cities and population.
1. Reverse the array of coin flips and save it.
1. Print out the population of one of the cities.
1. Print out a sentence about each item in the array of performing artists. For example:
  * `I think Pearl Jam is great.`
  * `I think Lady Gaga is great.`
  * `I think Pink Floyd is great.`


## Exercise 3

1. Print out the first two performing artists in that array.
1. For each of your favourite movies, print out a sentence about when the movie was released. For example:
  * `Avatar came out in 2009.`
  * `Mean Girls came out in 2004.`
  * `The Matrix came out in 1999.`
1. Sort and reverse the array of ages of your family. Save it and print it to the screen.
  * See if you can sort and reverse the array on one line!
1. Add "Beauty and the Beast" movie to your hash of movies information, but with a twist: the movie was released both in 1991 and in 2017. Print it out.


## Exercise 4

1. Print out all of the ages of your friends/family that are less than 30 (or any number where some ages will not be printed!).
1. Find and output the age of the oldest person in your friends/family array.
1. Count how many times you flipped 'heads' using the coin flips array.
1. You realize one of the performing artists in your list is no longer a favourite. Remove one of them from the array.
1. Pick a city in your city population hash and change its population.


## Exercise 5

1. Find the sum total of the population in the hash of cities.
1. Using your hash containing the names of your family and friends with their ages, print out one of two messages for each depending on their age. For example:
  * `Martha is old.`
  * `Stewart is young.`
  * `Holly is young.`
1. Print out the last two colours in your array of favourite colours.
1. Increase by 1 the age of everyone in your array of ages. Print it out.
1. Add two new colours to your array of favourite colours.


## Exercise 6
###### Composing Arrays and Hashes

1. Make a new hash that contains a list of movies for each year. Each list of movies should be an array. Below is some data you can use.
  * 1999: The Matrix, Star Wars: Episode 1, The Mummy
  * 2009: Avatar, Star Trek, District 9
  * 2019: How to Train Your Dragon 3, Toy Story 4, Star Wars: Episode 9

1. Make a new array that contains each row of the buttons on a phone. Each row should be an array.
  * The rows on a phone are: `1 2 3`, `4 5 6`, `7 8 9`, `* 0 #`

1. Make a new array that contains information about three countries. Each country should be a hash that has a name, a continent, and whether or not it is an island.


## Exercise 6
###### More Iteration

1. Output the message `"I will not skateboard in the halls"` 20 times.

1. Create an array consisting of the above message. It should appear in the array 20 times.

1. Create an array consisting of the numbers between 1 and 50.

1. Use an `each` loop to find the sum of the numbers in the above array.

1. Create a new array which has three of each number up to 50.
  * Ie. `[1, 1, 1, 2, 2, 2, 3, 3, 3, ... , 50, 50, 50]` and so on, up to 50.

1. Make a new array out all of the countries from the hash in Exercise 6 that are not islands. Print out both arrays.


## Exercise 7 - Stretch

*Note: Some of the questions below introduce new methods. If you are unable to answer these, don't worry!*

1. Make a new array that consists of all the elements of your `fav_colours` and `fav_artists` arrays. Then sort the array and output it.
  * Eg. `['Blue', 'Led Zeppelin', 'Pink', 'Pink Floyd', 'Stevie Wonder', 'Yellow']`

1. Using the array of ages and the array of favourite artists, output a message for each pair of items. For example:
  * `I <3 Green Day 75`
  * `I <3 Green Day 24`
  * ...
  * `I <3 Led Zeppelin 75`
  * `I <3 Led Zeppelin 24`
  * ...

1. One year has gone by. Use the `map` method to create a new array of the ages of your friends/relatives where all of the ages are increased by `1`. Output the result.

1. Use the `reduce` method to add up the numbers in your `ages` array. Print the total sum as a sentence using string interpolation.

1. Use the `select` method on your `coin_flips` array to make a new array that only includes the coin flips that successfully landed on 'heads'.
