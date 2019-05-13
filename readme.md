# Lab: Practice

No need to turn this in! Instead we will go over as a class together on the whiteboard, so make sure you have working code that you can explain for both problems! 

It is recommended to use [repl](repl.it) to write and test your code!

It is also recommended to work together with your classmates!

## 1. Fizzbuzz

Fizzbuzz is often used as a basic way to root out job candidates - often before they ever even reach an interview! So it's to your advantage to be able to do this problem really well!

#### Prerequesites

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

## 2. Get a valid guess! 

We'll come to a point in our careers as developers where no one gives us clear directions anymore. Instead, we have to do our own research on how to accomplish the objective. Hints are given below, but these are purposely chosen concepts we haven't covered in full!

#### Prerequesites

* Writing while loops in python
* Ability to research something you haven't learned yet
    * try/except! 
    * Casting a string to an integer!

#### Prompt 

Write a function called `get_guess` that initializes a `my_num` variable to `None`, then uses a `while` loop and `try`/`except` clauses to keep asking the user for input until they enter a number. The function, when called, should prompt the user for a number, and test if the input can be cast to an integer. If it can, then return this integer. If it cannot be cast to an integer, prompt the user for input again.

#### Example Output
```
Please give me a number between 1 and 10:
> no
That was not good input, please try again!
Please give me a number between 1 and 10:
> meh
That was not good input, please try again!
Please give me a number between 1 and 10:
> 5
```


## 3: Guess a number!

#### Prerequesites

* use `while` loops in python
* write conditionals in python
* `get_guess` function from #2
* import a module from the [python standard library](https://docs.python.org/2/library/index.html)
 
#### Prompt

Make your own version of the `Guess a Number` game that uses the `get_guess` function. Import the `random` python module and use it to generate a random integer and store it in a variable called `answer`. Initialize a `guess` variable to `false`. Print a statement asking the user to guess a number.

If the user's guess is:
* Higher than the `answer`: print `That is too high!`.
* Lower than the `answer`: print `That is too low!`.
* Exactly the `answer`: print `That's it! You win!`.
> For a bonus, change the success message to reflect the number of attemps a person made (for example, "It took you 5 tries, but you did it!")

Your program should keep prompting the user until they enter the correct answer.

#### Example Output
```
I'm thinking of a number between 1 and 10.
Please give me a number between 1 and 10:
> Eat my shorts!
That was not good input, please try again!
Please give me a number between 1 and 10:
> Ay, caramba!
That was not good input, please try again!
Please give me a number between 1 and 10:
> 5
That is too low!
Please give me a number between 1 and 10:
> 8
That's it! You win!
```

