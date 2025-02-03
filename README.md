Your C program for temperature conversion looks good and logically sound! Here's a brief breakdown of how it works:

celsiusToFahrenheit function: Converts a given temperature in Celsius to Fahrenheit using the formula (Celsius * 9/5) + 32 and prints the result.
fahrenheitToCelsius function: Converts a given temperature in Fahrenheit to Celsius using the formula (Fahrenheit - 32) * 5/9 and prints the result.
Main program: Displays a menu allowing the user to choose between Celsius to Fahrenheit conversion, Fahrenheit to Celsius conversion, or exiting the program. It takes user input and calls the appropriate function based on the user's choice.
Suggestions for Improvement:
Input validation: Currently, there is no input validation. For example, if the user enters a non-numeric value, the program may behave unexpectedly. You can add checks to ensure valid input.
Avoiding infinite loop: In the while(1) loop, you can handle an exit condition more explicitly, though the current logic of break on choice 3 works fine.
Other than that, it's a clean implementation! Would you like to add input validation or make any other changes?

output:
Temperature Converter
1. Celsius to Fahrenheit
2. Fahrenheit to Celsius
3. Exit
Enter your choice: 1
Enter the temperature: 25
25.00 Celsius = 77.00 Fahrenheit
