# CS50 Homework Hours Calculator

This program calculates the total or average number of hours spent on CS50 homework, given the number of weeks and hours for each week entered by the user.

## Getting Started

To run this program, you will need to have cs50.h installed, which can be downloaded from [here](https://cs50.readthedocs.io/libraries/cs50/c/).

To compile the program, open a terminal window and type the following command:
```sh
gcc -o homework_hours homework_hours.c -lcs50
```

To run the program, type the following command:
```sh
./homework_hours
```

## Usage

1. Enter the number of weeks taking CS50.
2. Enter the number of hours spent on homework for each week.
3. Enter "T" to calculate the total number of hours spent on homework, or "A" to calculate the average number of hours spent per week.

The program will then output the result in hours.

## Functions
### **`float calc_hours(int hours[], int weeks, char output)`**

This function calculates the total or average number of hours spent on homework.

**Parameters**
* **`hours`**: an array of integers representing the number of hours spent on homework for each week
* **`weeks`**: an integer representing the number of weeks
* **`output`**: a character representing the desired output type, either 'T' for total or 'A' for average

**Returns**
A floating-point number representing the total or average number of hours spent on homework, depending on the **`output`** parameter. If the **`output`** parameter is not 'T' or 'A', the function returns 0.