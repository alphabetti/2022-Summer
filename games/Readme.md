# Simple Games
## Introduction
In this section we'll write some games which use random numbers to provide interaction against a computer.

## What we'll use
Python comes with a load of functionality for handling random numbers inside the `random` module which you can import at the top of your python file.

> import random

There's full details of what this module contains at https://docs.python.org/3/library/random.html

But we'll mainly be using

> random.randint(0, 10) -- Generates a random number between 0 and 10
> random.choice(["apple", "banana", "cherry"]) -- Chooses one of the three options
> random.shuffle([0, 1, 2, 3, 4, 5, 6, 7, 8, 9]) -- shuffle a list randomly

> Computationally generating random numbers is actually a pretty hard problem to work out how to do.  How can you guarantee a computer can generate numbers which aren't predictable with enough observations?  Most computers use 'pseudo random numbers' which basically means - they're not really truly random but they're good enough for anything we want to do.  Often these use a _seed_ in the form of a number.  Given a seed, the computer will generate the same sequence of random outputs each time.  Most random number generators use the current time as the seed so you get different outcomes each time.

We'll also want to interact with the person playing the game.  We can use the `input` command to do this

> yourName = input('What is your name?')


