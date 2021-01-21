Part 1
Create a program that counts the number of times a six of a seven is rolled when rolling a pair a dice a given number of times. The program should ask the user how many times they would like to roll the dice. A sample of the code running might look like:

Welcome to the dice rolling program. This program will tell you how many times you rolled a 6 or 7.
Enter number of rolls:
5
Roll 1 is 9 (5+4)
Roll 2 is 6 (3+3)
Roll 3 is 7 (3+4)
Roll 4 is 6 (4+2)
Roll 5 is 4 (2+2)

Dice roll statistics:
6s: 2
7s: 1

Write this code into the count_six_and_seven.c file provided. Notice that the file currently has code in it to show you how to generate a random number.

Part 2
Copy count_six_and_seven.c into histogram.c. Modify histogram.c such that it will generate a histogram of the total number of dice rolls for each number. A sample of this program might look like:

Welcome to dice stats. This program will generate a histogram of how many times each number was rolled in a given set of rolls.
Enter number of rolls:
100
Dice Roll Histogram
 2: ********
 3: ****
 4: ********
 5: **************
 6: *************
 7: *************
 8: **********
 9: *************
10: *********
11: *******
12: *
