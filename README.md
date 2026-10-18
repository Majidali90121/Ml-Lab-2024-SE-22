# Machine Learning Labs

This repository contains practical lab exercises completed while learning Python and preparing for Machine Learning.

## Lab 1: Python Basics

### Topics Covered

1. **Exponentiation and arithmetic operators** — using `**` to calculate powers.
2. **String methods** — using `.split()` to separate a sentence into a list of words.
3. **String formatting** — using `.format()` to insert values into a sentence.
4. **Nested list indexing** — accessing a value inside a list nested within other lists.
5. **Nested dictionary and list indexing** — retrieving a value from a complex dictionary structure.
6. **Lists vs. tuples** — understanding that lists are mutable while tuples are immutable.
7. **Functions and string splitting** — extracting a domain from an email address.
8. **Case-insensitive string searching** — checking whether a string contains the word `dog`.
9. **Counting text occurrences** — counting occurrences of `dog` without distinguishing capitalization.
10. **Conditional logic** — implementing speeding-ticket rules with an additional birthday allowance.

## Requirements

- Python 3
- Any Python editor or notebook environment, such as VS Code, Jupyter Notebook, or Anaconda

No external Python packages are required for these exercises.

## How to Run

1. Open the Lab 1 Python notebook or Python file in your preferred editor.
2. Run the cells or execute the Python file.
3. Review the output and experiment with different input values.

## Notes and Improvements

- In Exercise 6, assigning a new value to `t[0]` raises a `TypeError` because tuples are immutable. Run that line separately if you want to test the error; otherwise, it prevents later lines in the same notebook cell from running.
- In Exercise 9, use `text.lower().count('dog')` to count both `dog` and `Dog`.
- In Exercise 10, subtracting 5 from the speed on a birthday implements the stated 5 mph allowance.

## Repository Structure

```text
Machine-Learning-Labs/
├── README.md
└── Lab-1/
    └── (add your Python notebook here)
```

## Learning Goal

Build a foundation in Python programming before moving on to data analysis and Machine Learning concepts.

---

Created for educational and practice purposes.
