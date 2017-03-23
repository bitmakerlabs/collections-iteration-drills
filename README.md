
# Exercises on Collections and Iteration

## What You Will Learn

This assignment will provide repetitious exercises in order to practice dealing with collections of different types and iterating over them.

## Prerequisites

* variables
* string interpolation
* conditionals/flow control
* had lesson on collections/iteration



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
  * your favourite movie names and their year of creation [COULD BE BETTER FOR ARRAYS IN HASHES]
  * three cities of the world and their population
  * the names of your siblings/cousins/friends and their ages


## Exercise 1
###### Accessing Values from Arrays and Hashes

1. For all of the arrays above, print out:
  * the first element
  * the last element
  * the first two elements
  * the last two elements

1. For all of the hashes above, print out:
  * one of the stored values


## Exercise 2
###### Sorting and Reversing

1. For each of your arrays, print out the reversed version of that array.
1. For each of your arrays, print out the sorted version of that array.
1. For each of your arrays, sort the array, reverse it, and then print it out.
  * See if you can do the above all on one line!


## Exercise 3
###### Iteration

1. For each of your arrays, print out a sentence about each item in the array.
  * For example, for your `fav_colours` array, you might print:
    * `My favourite colour is red.`
    * `My favourite colour is green.`
    * `My favourite colour is blue.`


2. For each of your hashes, print out a sentence that includes both the key and the value of the item.
  * For example, for the hash storing the names and ages of your friends/relatives, you might get:
    * `Mary is 8 years old.`
    * `Chantal is 33 years old.`
    * `Tan is 42 years old.`


## Exercise 4
###### Adding New Elements

1. Append an element to each one of your arrays.

1. Add a new key/value pair to each one of your hashes.


## Exercise 5
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
