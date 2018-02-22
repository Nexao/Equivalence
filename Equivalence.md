1. Make equivalence classes for the input variable for this method
public boolean isEven(int n)

This class will go TRUE, if the input is an even number, for example 2,4,6,10 and so on

And it will go FALSE, if the input is uneven, for example 1,3,5,73


2. Make equivalances classes for an input variable that represents a mortgage applicant's salary. The valid range is $1000 pr.month to $75.000 pr.month

The range of the mortgage is between 1000$ and 75.000$

< 1000 is INVALID
> 75.000 is INVALID
1000 - 75.0000 is VALID

The first two are invalid because they are both outside of the range, therefore a number of forexample 65$ is will give the same error as 85.000$, as the number is outside of the range.

3. Make equivalances classes for the input variables for this method.

Public static int getNumDaysInMonth (int month, int year)

int month:
< 1 = INVALID
> 12 = INVALID
1 - 12 = VALID 

The int for month can only be between 1 to 12, as we only have 12 months in a year.

int year:
A year can be any INTEGER number (it can't be point something), as we can both work with years before 0 (Before christ) and any number in the future for example year 10.000, but it depends on the application as for what you can work with.


# Boundry analasyis

1.

Here it's not possible to do, as there's no range for either even or uneven numbers.

2. 

-------1000---------------75.000---------

Testing 999 : INVALID

Testing 1000 : VALID

Testing 40.000 : VALID

Testing 75.000 : VALID

Testing 75.001 : INVALID

3. 

Months:
---1----12---

Testing 0 : INVALID

Testing 1 : VALID

Testing 6 : VALID

Testing 12 : VALID

Testing 13 : INVALID

Years can't be tested, as the range is unlimited


Decision table

![alt text](http://prntscr.com/iibvyj)

# H1 State Transition

1.

![alt text](https://scontent-amt2-1.xx.fbcdn.net/v/t35.0-12/s2048x2048/28343147_10215695213151695_1695004671_o.jpg?oh=88cb7ac588fa52f20a3f79212b68f7c7&oe=5A9109AF)

2.

S1 - Empty list
S2 - Elements in list
S3 - Index out of bounds
S4 - Expanded List

![alt text](https://scontent-amt2-1.xx.fbcdn.net/v/t35.0-12/s2048x2048/28342919_10215695710604131_1296579400_o.jpg?oh=962023c3c85ac6d1cf3722b015c63445&oe=5A91214C)

3.

