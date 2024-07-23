# Calculating Factorial Using Recursion

This project demonstrates how to calculate the factorial of a number using a recursive function in Python.

## Steps to Calculate Factorial:

1. **Take Input from User**: Prompt the user to enter a number and convert the input to an integer.
2. **Define the Factorial Function**: The factorial of a number \( n \) is calculated as \( n \times (n-1)! \).
3. **Base Case for Recursion**: The recursion will stop when \( n = 0 \) and return \( 0! = 1 \).
4. **Print the Output**: Display the factorial of the entered number.

## Example Code:

```python
# factorial.py

def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)

if __name__ == "__main__":
    number = int(input("Enter a number: "))
    print(f"The factorial of {number} is {factorial(number)}")
