# Milestone 1 - Temperature Advisor
This is my milestone 1 for my Python Class with Uplift Code Camp.

## What the Program Does
This program advises the user if the temperature is hot, warm, cool, or cold and it suggests a clothing based on the temperature today. It also checks converts the input temperature from integer to float because usually temperature have decimal points. This program also has a checker that uses `assert` function to see if the result is correct.

## How to Run It
It runs when you click `shift` + `enter` and then it will ask you to input a number, it can be integer or float as it will convert them to float. 

## One Challenge You Debugged
What challenged me on this code is how am I going to add an input as when I tried it a few times, it had an error and upon researching the problem, it leads me on using the while loop and add an input. At first, I thought it was wrong as it keeps loading but I noticed that on the box above it was asking me to input the temperature. However, when I tried to input a string on the input, the result is ValueError so I added a try and except. Upon adding the except, it solved the problem and it is printing "Please enter a valid number for the temperature.".
