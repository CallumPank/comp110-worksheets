***

a) This algorithm looks through both indexes i and j and checks whether i is not equal to j and whether index[i] is equal to index [j]if they are, then the list has a duplicate within it and the code returns
true.  If there is not a duplicate, then it will return false and end the procedure.
 
b) Quadratic will have the worst running time because the algorithm must check index i before and at the same point as index j in the list. For example if the program is comparing item 1 which is i in the list it will check it against item 0, 1, 2 ,3 which is j in the list, this will be written as n^2.
  
c) The algorithm, is still correct because the code checks the previous items in the list with the new item meaning that once the code has completed it will have compared the items but not have made any duplicate comparisons.
 
d) The algorithm runs twice as fast because it only has to run half the comparisons after taking away the duplicate comparisons.
 
e) The time complexity is not quadratic because index i and index j are not going to be running through every value now and comparing them. Instead now when the program runs index j one step behind index i, this means that it stops one step behind index i. It then checks for duplicates, this mean that duplicates will be found anyway becuase the program goes through the entire list.
 
f) O (n log n) - https://wiki.python.org/moin/TimeComplexity
 
g) O(n log n) because the loop in  lines 4-8 of the program is 0(n), but the 0(n log n) dominates the 0(n).
 
h) The second algorithm will run faster because it is 0(n log n) which means that it will run faster than the first algorithm because the first algorithm is 0(n). So when there is a large list it means that the second algorithm will run slower.

i) The reason that a programmer may run a slower program is because they have a small list.That does not have a lot of values. 

***









































 


