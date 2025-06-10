# Simple Calculator in Python

This is a basic calculator program written in Python that performs addition, subtraction, multiplication, and division on two numbers provided by the user.

## How to Use

1.  **Clone the repository:**

    ```bash
    git clone <repository_url>
    ```

2.  **Navigate to the directory:**

    ```bash
    cd <repository_directory>
    ```

3.  **Run the script:**

    ```bash
    python your_script_name.py
    ```

    (Replace `your_script_name.py` with the actual name of your Python file.)

4.  **Input:** The program will prompt you to enter two numbers.  Enter the first number and press Enter, then enter the second number and press Enter.

5.  **Output:** The program will then display the results of the addition, subtraction, multiplication, and division operations.

## Code

```python
a = int(input("Enter the first Number:- "))
b = int(input("Enter the Second Number:- "))

Addition1 = a + b
Subtraction1 = a - b
Multiplication1 = a * b
Division1 = a / b

print("Addition ", Addition1)
print("Subtraction ", Subtraction1)
print("Multiplication ", Multiplication1)
print("Division ", Division1)



---------------------------------------------------------------------------



# Greeting Program in Python

A simple Python script that takes a first name and last name as input and prints a personalized greeting.

## Usage

Run the script, enter your first and last names when prompted. The program will then display a greeting message.

## Code

```python
firstname=input("Enter the first Name:- ")
lastname=input("Enter the Second Name:-")
join1 = firstname + " " +lastname+"!"

print("Hello,",join1,"Welcome to the python program" )

