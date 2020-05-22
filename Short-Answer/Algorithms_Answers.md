#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)O(n) The algorithm adds n^2 to the variable n times.


b)O(nlogn) The for-loop will run n times, and each time, the while loop will run log(n) (base 2) times, rounded up. Multiply those together and you get nlog(n).


c)O(n) The function will recurse n times

## Exercise II

This is a binary search. Runtime is O(log n). Algorithm below:

Start at the middle floor between where you are and the top.
Repeat below until floor f is found
	Drop the egg.
	If it breaks, move to the middle floor beteween where you are and the ground floor.
	If it doesn't break, move to the middle floor between where you are and the top floor.
	Once you find the highest floor it doesn't break on, that's floor f.
