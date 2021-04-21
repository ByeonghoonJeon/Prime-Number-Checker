# Prime number checker
Code for checking if a number is prime number.
Also it shows which numbers can divide the number that you are enquiring.

# 1 Step to use.

1. Input myterious number to figure out whether it is a prime number or not!

If it is a prime number, it will exhibit "n is a prime number"
or not, it will exhibit numbers that can divided 'n' without remainder.

# How it works

First, it checks whether user input is valid or not with .isdigit()
Until user inputs designed answer, which is number without decimal point, it repeatedly ask to input valid number.

After that when a valid input is gained,  user's input is divided through all of numbers between 1 and the user's number itself.
If remainder is zero, numbers are collected to a list.

If list includes only 1 and user's number, it determines the number as a prime number. Otherwise, it shows every numbers that can devide user's number without remainder.

The end.
