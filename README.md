# Unit 4 Challenge: Console Finances

## Overview

We are going to analyse a chunk of data containing months and profit/loses for each one, and find out the total number of months, the total benefit (let's hope it is not negative!) and which single month did we obtain the single bigger profit and which single month did we register the single biggest lose.

## Steps

1. I started by setting up the variables we are going to work with, max balance change and its month, as well as the min balance change and its month. I also needed to define the total balance add up.

2. I assumed that the finances variable did not repeat any month, and I set that variable lenght as the number of months.

3. I created a for loop setting the variable "month_balance". This loop will go on as many times as number of months.

4. I know that the variable given is a matrix, so I defined the month as the first argument of each element of the variable (0) and balance change for the second (1)

5. Using that, I calculated the sum of balance change to obtain and define the total balance change.

6. Inside the for loop I set up to "if"s. The first one runs through all the values and retains the biggest one and compares it to the next one. If the next one is bigger, then it retains that one as "max_balance_change" and so on until it compares all the values. The second one does the same with the minimum 

7. Finally, the total / number of months reveal the average change.
   

## Review in change

I spoke with a TA and I understood that the exercice wanted us to calculate the biggest profit and biggest lose for each month COMPARED to the previous month, not the biggest profit and the lowest profit out of the ones displayed. I need some time to work it out and change it

## Copyright

Work done by Alexis Nadir Garcia Benchakhtir