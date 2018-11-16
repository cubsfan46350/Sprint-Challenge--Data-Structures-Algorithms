Add your answers to the Algorithms exercises here.

a) O(n). The variable a is dependent on how long the while loop is executed due to the constraints that the variable n^3 is. So, as long as the variable a is less than n cubed added to itself, the while loop will run. 

b) O(n^3). The for loop is dependent on two processes completing before it loops back up to change the sum variable.

c) O(n). The function is dependent on running as long as the variable is not equal to zero. If the variable is equal to zero, the function just returns zero.


Exercise 2:

Since you have an infinite amount of eggs, you would first start dropping eggs at the middle floor of the building. You would continue going down a floor at a time until you reach a floor that when an egg is dropped does not break. Once you reach this point, the floor above the floor that the egg didn't break at would be floor f. Also, you would do the same starting from the obtained floor f. You would keep dropping eggs by going up a floor until an egg doesn't break.