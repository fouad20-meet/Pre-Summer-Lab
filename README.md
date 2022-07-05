# Pre Summer Python Review 2 Lab

## Objective: 
During this lab: 
- You will review the python material we went over.
- You will be more familiarized with python Dictionaries and Lists!


## Instructions:
> Before we start, make sure to create a new Repl.it and call it "Pre Summer Review"!

### Part 1: 
In `main.py` -
1. Define an empty dictionary and call it `fav_food`:
    - This dictionary will contain names as keys, and different food as values.
  
2. Creating a while loop:
    - Take an input from the user and display the message: ` "Enter any key to continue, and 'end' to stop: " ` and assign it to the variable x.
    - Create a while loop that runs while x is not equal to ` "end" `.
    - **Remember to take x again as an input inside the while loop in order not to have an endless loop**
    
3. Adding to the dictionary:
    In the `while` loop -
    - Take name as an input from the user, and assign it to the variable `name`.
    - Take favorite food as an input from the user, and assign it to the variable `fav_food`.
    - Add to the dictionary a new key and value, with `name` as the key and `fav_food` as the value.

**Good Job! Remember to show your wonderful work to your Instructor.**

### Part 2: 
In cryptography, the easiest form of a cipher is known as a **[Caesar cipher](https://en.wikipedia.org/wiki/Caesar_cipher)**.  
In a Caesar cipher, we encode letters by ***shifting*** the characters in the **alphabet** by some `value` (usually by `3`).  
Here is a Python dictionary that represents the full encoder mapping used in a Caesar cipher.  
```python
encoder_caesar = {'a':'d','b':'e','c':'f','d':'g','e':'h','f':'i','g':'j','h':'k','i':'l','j':'m','k':'n','l':'o','m':'p','n':'q','o':'r','p':'s','q':'t','r':'u','s':'v','t':'w','u':'x','v':'y','w':'z','x':'a','y':'b','z':'c'}
```

1. Add this dictionary to your code.
2. Write a **function** that takes a `string` as a parameter and returns the same string but shifted by 3 letters - according to the Ceasar cipher. 
  - Use the encoder_caesar dictionary.
  - Example: `"meet"` - should be returned as `"phhw"`.
  - *Hint:* check how to print the value of a specific key in a python dictionary.


##### Great job!
##### Call an Instructor/TA to check your completed tasks
 
 


## Bonus:
According to Wikipedia: In **number theory**, a **perfect** number is a positive integer that is equal to the sum/total of its proper positive divisors.  
  
**Example :** 
- The first perfect number is 6, because 1, 2, and 3 are its proper positive divisors, and `1 + 2 + 3 = 6`. 
- The next perfect number is `28 = 1 + 2 + 4 + 7 + 14`. This is followed by the perfect numbers `496` and `8128`.  
  
  
1. Write a Python function to check whether a number is perfect or not if yes the function returns True, if no the function returns False.
 
1. If the number is a perfect number write another function that will return a list of the numbers’ proper positive divisors.

1. if false write another function that will return a string saying “The number is not perfect.”

**Good Job! Remember to show your Brilliant work to your Instructors and TAs.**



<img src="https://i.stack.imgur.com/D3ypD.gif" width="350">
