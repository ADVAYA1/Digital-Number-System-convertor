
# Digital Number System Conversion Project

## Project Overview

The **Digital Number System Conversion Project** is a Java-based application that facilitates the conversion of decimal numbers into binary, octal, and hexadecimal representations. In addition to number conversions, this project includes functionality for manipulating Boolean expressions, specifically converting them into **Sum of Products (SOP)** and **Product of Sums (POS)** forms. It also provides tools for understanding and working with **minterms**, **maxterms**, and generating **truth tables** for Boolean functions. This project is useful for learning and understanding digital logic systems, simplifying Boolean expressions, and visualizing conversions between different number systems.

## Project Files

1. **`Main.java`**  
   This is the core file containing the main logic of the project. It handles:
   - Converting decimal numbers to binary, octal, and hexadecimal formats.
   - Simplifying Boolean expressions and converting them to **SOP** and **POS** forms.
   - Generating **minterms** and **maxterms** for a given Boolean expression.
   - Offering functionality for working with truth tables to understand the Boolean logic behind the expressions.

2. **`Main.class`**  
   This is the compiled version of `Main.java`. It contains the bytecode of the Java program and can be run using the Java runtime environment.

3. **`Main$RoundedButton.class`**  
   This inner class customizes the appearance of buttons in the graphical user interface (GUI) by overriding the `paint` method to create rounded buttons. This enhances the look of the GUI, making it more user-friendly and visually appealing.

4. **`Main.html`**  
   The HTML file provides a user interface for interacting with the Java application. It may include forms where users can input either decimal numbers for conversion or Boolean expressions for processing, displaying the results directly in a web browser.

## UI
![image](https://github.com/user-attachments/assets/4a5ac815-0d0c-4204-b3a6-e39b52f0579d)


## Features

- **Decimal Conversion**: Converts decimal numbers into binary, octal, and hexadecimal formats.
- **Boolean Expression Simplification**: Allows users to input Boolean expressions and converts them into **SOP (Sum of Products)** and **POS (Product of Sums)** forms.
- **Minterms and Maxterms Generation**: Generates the **minterms** (AND of variables) and **maxterms** (OR of variables) corresponding to a Boolean function.
- **Truth Table Generation**: Creates a truth table for the given Boolean function, helping visualize the function’s output across all combinations of inputs.

## Key Concepts

### **Minterms**
A **minterm** is a product (AND operation) of all variables in a Boolean function, where each variable is either complemented or in its original form. Each **minterm** represents a row in the truth table where the output of the Boolean function is **1** (true). For example, in a Boolean function with three variables \( A, B, C \), a minterm could be:
```
A'B'C
```
This represents the AND operation of \( A' \) (the negation of A), \( B \), and \( C \).

### **Maxterms**
A **maxterm** is a sum (OR operation) of all variables in a Boolean function, where each variable is either complemented or in its original form. Each **maxterm** corresponds to a row in the truth table where the output of the Boolean function is **0** (false). For example, a maxterm for the same 3-variable Boolean function could be:
```
A + B' + C
```
This represents the OR operation of \( A \), the negation of \( B \), and \( C \).

### **Sum of Products (SOP)**
The **Sum of Products (SOP)** form is a Boolean expression that is the sum (OR operation) of multiple **minterms**. It represents the function as a disjunction (OR) of conjunctions (ANDs) of literals. SOP is useful for implementing Boolean functions, particularly in logic gates or digital circuits.

### **Product of Sums (POS)**
The **Product of Sums (POS)** form is a Boolean expression that is the product (AND operation) of multiple **maxterms**. It is the opposite of SOP and represents the Boolean function as a conjunction (AND) of disjunctions (ORs) of literals. POS is typically used for minimizing and implementing logic circuits, especially in digital designs.

### **Truth Table**
A **truth table** is a tabular representation of all possible input values and their corresponding output values for a Boolean function. It shows how the output of the Boolean function changes for all combinations of the input variables.

## Usage

To compile and run the program:

1. **Compile the Code**  
   Open a terminal or command prompt and navigate to the directory where the `Main.java` file is located. Run the following command to compile the Java code:
   ```bash
   javac Main.java
   ```
   This will generate the `Main.class` bytecode file.

2. **Run the Application**  
   After compilation, run the program with:
   ```bash
   java Main
   ```
   This will start the program and prompt you to input either a decimal number for conversion or a Boolean expression for simplification.

3. **Input**
   - **For Decimal Conversion**: Enter a decimal number when prompted. The program will output the binary, octal, and hexadecimal equivalents.
   - **For Boolean Expression**: Enter a Boolean expression using variables such as `A`, `B`, `C`, etc., and the program will provide the **SOP**, **POS**, **minterms**, and **maxterms**.

4. **Output**
   - For decimal numbers, the program will output the corresponding binary, octal, and hexadecimal representations.
   - For Boolean expressions, the program will display the **SOP**, **POS**, **minterms**, **maxterms**, and the **truth table** for the given expression.

## Conclusion

This project is a powerful tool for understanding and working with digital number systems and Boolean logic. It helps users to visualize number conversions and simplifies Boolean expressions for use in digital circuits. The program is ideal for students and anyone interested in learning about digital logic design, truth tables, and number system conversions.
```
