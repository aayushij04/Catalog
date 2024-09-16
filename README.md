#Polynomial Constant Term Calculator
##This C++ program computes the constant term of a polynomial using Lagrange interpolation.
##The polynomial is determined from given points, and the constant term is extracted based on the polynomial's degree.

#Features
##Lagrange Interpolation: Uses Lagrange interpolation to compute the polynomial's constant term.
#JSON Input: Parses and decodes polynomial data from JSON format.
#Compilation and Execution
##Compile the Program

To compile the program, use the following command:

bash
Copy code
g++ -o polynomial_calculator polynomial_calculator.cpp
Run the Program

Execute the program and provide JSON input when prompted:

bash
Copy code
./polynomial_calculator
Dependencies
C++ Standard Library: For basic functionalities and I/O operations.
nlohmann/json: For parsing JSON data.
