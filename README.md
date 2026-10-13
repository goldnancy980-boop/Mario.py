# Mario Double Pyramid

A Python command-line program that prompts users to enter a height between 1 and 8 and prints two side-by-side pyramids using hash (`#`) symbols.

## Features

* **User Input:** Prompts the user to enter the pyramid height.
* **Input Validation:** Accepts only heights between 1 and 8.
* **Double Pyramid:** Prints two pyramids side by side with a two-space gap between them.
* **Right Alignment:** Aligns the left pyramid using spaces.
* **Loop-Based Construction:** Uses `while` and nested `for` loops to validate input and construct the pyramids.

## Built With

* **Python 3**
* **CS50 Python Library** — Provides the `get_int()` function for collecting integer input.

## Requirements

* Python 3
* CS50 Python library

## Installation

Install the CS50 Python library by running the following command in your terminal:

```bash
python -m pip install cs50
```

## How to Run

1. Clone or download this repository.

2. Open your terminal in the project directory.

3. Run the program:

   ```bash
   python mario.py
   ```

4. Enter a height between 1 and 8 when prompted.

## Why Use `get_int()`?

I used `get_int()` from the CS50 Python library because this project was part of a CS50 problem set (PSET). Although the program could also be implemented using Python's built-in `input()` function with appropriate input conversion and validation, `get_int()` conveniently handles non-integer inputs by prompting the user again.

## Example Output

For an input of `4`:

```text
Height: 4
   #  #
  ##  ##
 ###  ###
####  ####
```

## Testing

Test with heights from `1` to `8` to verify the pyramid output. Inputs outside this range should prompt the user to enter a valid height again.

## Concepts Practiced

* Variables and user input
* Conditional statements
* `while` loops
* Nested `for` loops
* Input validation
* The `range()` function
* Printing characters and controlling line endings

## Purpose

This program I built demonstrates my understanding of fundamental Python programming concepts through a simple pyramid-building exercise.
