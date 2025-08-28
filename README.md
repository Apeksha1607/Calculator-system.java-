

# Simple Calculator Java Program

A basic Java console application that performs arithmetic operations — addition, subtraction, multiplication, and division — on two numbers input by the user.

## Features

* Input two numbers and an arithmetic operator (+, -, \*, /).
* Performs the calculation based on the chosen operator.
* Displays the result or an error message for invalid operations.

## How to Run

1. Ensure you have Java installed on your system (JDK 8 or later recommended).
2. Compile the program:

```bash
javac cal.java
```

3. Run the program:

```bash
java cal
```

4. Follow the prompts to enter numbers and an operator.

## Sample Interaction

```
Enter numbers:
10 5
Enter the operation:
+
Answer is15.0
```

## Code Structure

* Class `cal`:

  * Fields: `num1`, `num2` (input numbers), `ans` (answer), and `op` (operator).
  * Method `input()`: Takes input from the user.
  * Method `calculation()`: Performs the arithmetic operation based on the operator.
* `main` method: Creates an instance of `cal`, takes input, and performs calculation.

## Notes

* Division by zero is not explicitly handled — be cautious with inputs.
* Only supports four basic operations.

## License

This project is open source and free to use.

---

