# NumberGuessingGame
A number guessing game I programmed in VS studio code using Java.

# Reflection

## Introduction/Purpose
The purpose of this program is for the user to guess the correct number that the program has randomly generated. Depending on the users guess, the program will tell you if your guess is either lower or higher than the correct random number. Then the program will allow you to re-enter a new guess until the user gets it correct.

## Problem I ran into and how I solved them
The first issue I ran into was randomly generating a number. I counteracted this problem by setting a minimum and a maximum amount for the random value. Then I created a random value variable where I equalled (int)Math.floor(Math.random)* (max - min + 1) + min. This allowed for the program to create a random value ebtween the maximum and minimum amount. THe next problem I ran into was trying to get the program to tell the user if the value was higher or lower than the correct value. This was supposed to be ongoing until the user guessed the correct number. First, I tried to create a for loop, however I noticed that my condition didn't really make sense. Then I tried a do while loop but I still kept running into the same problem (where it would only tell the user one time if the value is lower or higher than the correct value). I tried to change the condition and realized I could create a while loop with two conditions, utilzing the or operator. This worked perfectly and allow my number guessing game to keep going until the user got the value correct.
