Homework--2
===========

What it does:

This program takes in a number (n) and will tell the user if it is a perfect number or not. 
If the number is (6, 28, 496, 8128.. etc) then the program will print “you found a perfect number!!” 
if it is not, the program will print “That number is not perfect...” 

How it works:

The program starts out by defining add = 0, and then enters a for loop, the loop is set using 
xrange which will keep it between 1 and the number the user enters. As the program progresses 
through, it tests each numbers divisibility (if mod equals 0 then it found a number which it 
is divisible by) It will then take that number (currently set as i) and add it to add. Once the 
for loop is complete the program compares add (which is now the sum of all the divisors of the 
entered number) and compares it to the original number entered. If they are equal then you have 
found a perfect number
