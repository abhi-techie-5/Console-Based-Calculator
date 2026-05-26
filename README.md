# Console-Based-Calculator


A Python-based console calculator project that performs multiple mathematical operations using user input and NumPy.

## Features

* Addition of multiple numbers
* Subtraction of multiple numbers
* Multiplication of multiple numbers
* Division with zero-division handling
* User-friendly console interaction
* Uses NumPy for efficient mathematical operations

## Technologies Used

* Python 3
* NumPy
* Jupyter Notebook

## Project Structure

```bash
project1.ipynb   # Main calculator project file
```

## How It Works

The program first asks the user how many numbers they want to enter. After taking input values, it performs the selected mathematical operation.

### Operations Included

#### 1. Addition

Adds all entered numbers using NumPy.

#### 2. Subtraction

Subtracts numbers one by one from the first number.

#### 3. Multiplication

Finds the product of all entered numbers.

#### 4. Division

Divides numbers sequentially and handles division-by-zero errors.

## Installation

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/your-repository-name.git
```

### Step 2: Move into the Project Folder

```bash
cd your-repository-name
```

### Step 3: Install Required Library

```bash
pip install numpy
```

## Run the Project

### Using Jupyter Notebook

```bash
jupyter notebook
```

Open `project1.ipynb` and run the cells.

### Using Python

You can also convert the notebook into a Python file and run it:

```bash
python project1.py
```

## Example Output

```text
How many numbers do you want to enter? : 3
Enter the number: 10
Enter the number: 20
Enter the number: 30

The addition of numbers are : 60
```

## Error Handling

The division function checks for division by zero and displays an error message instead of crashing.

```text
Error: Division by zero!
```

## Future Improvements

* Add menu-driven interface
* Add advanced scientific calculations
* Add graphical user interface (GUI)
* Save calculation history
* Add unit conversion features

## Learning Objectives

This project helps beginners understand:

* Python functions
* Loops and conditions
* List handling
* NumPy operations
* User input handling
* Exception and error handling

## Author

Created by Abhishek

## License

This project is open-source and free to use for learning purposes.

