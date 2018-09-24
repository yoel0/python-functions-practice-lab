# Lab: Functions Practice

No need to turn this in! Instead we will go over as a class together on the whiteboard, so make sure you have working code that you can explain for both problems! 

It is recommended to use [repl](repl.it) to write and test your code!

It is also recommended to work together with your classmates!

## 1. Fizzbuzz

Fizzbuzz is often used as a basic way to root out job candidates - often before they ever even reach an interview! So it's to your advantage to be able to do this problem really well!

**Prerequisites:**

* Writing a function in python
* Using parameters/arguments in python functions
* Writing a loop in python
* Writing conditional statements in python
* Using modulus
* Using print to output text

#### Prompt

Write a function called `fizzbuzz` that has a parameter `n`. `fizzbuzz` takes a numerical argument for the value of `n`, which is the maximum value to print up to. For example, if I gave you the number 10, I would expect your program to start at 1 and print up to 10.

Additionally, your function should do the following:

* If a number is divisible by 3, print `fizz`
* If a number is divisible by 5, print `buzz`
* If a number is divisible by 3 AND 5, print `fizzbuzz`
* If none of the above are true, just print the number itself

#### Example Usage

```python
fizzbuzz(20)
```

#### Expected Output

```
1
2
fizz
4
buzz
fizz
7
8
fizz
buzz
11
fizz
13
14
fizzbuzz
16
17
fizz
19
buzz
```

## 2. Guess a number! 

We'll come to a point in our careers as developers where no one gives us clear directions anymore. Instead, we have to do our own research on how to accomplish the objective. Hints are given below, but these are purposely chosen concepts we haven't covered in full!

**Prerequesites:**

* Writing while loops in python
* Ability to research something you haven't learned yet
    * including a package to generate random numbers! 
    * Casting a string to an integer!

#### Prompt 

Make your own version of the `Guess a Number` game. Generate a random integer and store it in a variable called `answer`. Print a statement asking the user to guess a number.

If the user's guess is:
* Higher than the `answer`: print `That is too high!`.
* Lower than the `answer`: print `That is too low!`.
* Exactly the `answer`: print `That's it! You win!`.

Your program should keep prompting the user until they enter the correct answer.

#### Example Output
```
I'm thinking of a number between 1 and 10.
Please guess what it is:
> 4
That is too low!
> 8
That is too high!
> 6
That's it! You win!
```

> **Hint 1:** User input comes to you as a string. How can you make it into an integer so you can properly compare the user's guess with the `answer` (which is an integer)?
> **Hint 2:** You can set a variable to `False` or `True`.

## 3: D'oh!

**Prerequisites:**

* Ability to research something you haven't learned yet
    * Using `try`/`except` statements and error handling.
    * Using the `continue` keyword inside a loop


#### Prompt

Bart Simpson has gotten ahold of your program from Problem 2 and started entering a bunch of values that are NOT numbers! How do you handle it?

Create a new repl with your code from Problem 2 and modify it to print `D'oh! That is NOT a number, Bart!` if the user doesn't enter an integer.

#### Example Output
```
I'm thinking of a number between 1 and 10.
Please guess what it is:
> Eat my shorts!
D'oh! That is NOT a number, Bart!
Please guess what it is:
> Ay, caramba!
D'oh! That is NOT a number, Bart!
Please guess what it is:
> 5
That is too low!
Please guess what it is:
> 8
That's it! You win!
```

> **Hint:** The `continue` keyword can be called in a loop and means "skip the rest of this loop iteration." It may be useful to call this in an `except` clause.

