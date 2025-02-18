## Python Function Challenge: Temperature Converter

Your task is to create a temperature conversion program using Python functions. This program will allow users to convert temperatures between Celsius and Fahrenheit scales.

**Requirements:**

1. Create two functions:
   - `celsius_to_fahrenheit(celsius)`: Converts Celsius to Fahrenheit
   - `fahrenheit_to_celsius(fahrenheit)`: Converts Fahrenheit to Celsius

2. Implement a main menu function that displays options and returns the user's choice.

3. Use a while loop to keep the program running until the user chooses to quit.

**Function Formulas:**
- Celsius to Fahrenheit: $$F = (C \times 9/5) + 32$$
- Fahrenheit to Celsius: $$C = (F - 32) \times 5/9$$

**Program Structure:**

```python
def celsius_to_fahrenheit(celsius):
    # Your code here

def fahrenheit_to_celsius(fahrenheit):
    # Your code here

def menu():
    # Your code here

def main():
    # Your code here

# Call the main function to start the program
main()
```

**Bonus Challenge:**
Add a third conversion option for Kelvin, including functions to convert to and from Kelvin.

## Submission:  Submit your code here and click "mark as done" on Google Classroom.


def celsius_to_fahrenheit(celsius):
   return (celsius * 9/5) + 32

def fahrenheit_to_celsius(fahrenheit):
    return (fahrenheit) - 32 * 5/9

def kelvin_to_celsius (kelvin):
    return (kelvin) - 273.15

def celsius_to_kelvin (celsius):
    return (celsius) + 273.15

def kelvin_to_fahrenheit(kelvin):
    return (kelvin - 273.15) * 1.8 + 32

def fahrenheit_to_kelvin(kelvin):
    return (fahrenheit - 32) * 5/9 + 273.15

def menu():
    print("Temperature Converter Menu:")
    print("1. Celsius to Fahrenheit")
    print("2. Fahrenheit to Celsius")
    print("3. Kelvin to Celsius")
    print("4. Celsius to Kelvin")
    print("5. Kelvin to Fahrenheit")
    print("6. Fahrenheit to Kelvin")
    print("7. EXIT")
