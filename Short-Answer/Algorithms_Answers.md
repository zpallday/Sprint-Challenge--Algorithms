#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) a = 0  
    while (a < n * n * n): 
      a = a + n * n         

      O(n) -- linear.When the N is increases the amount of steps for loops are also increases.


b) O(n^2) For loop is O(n) becuase it will increase the size linear with n, and also the while loop is O(n). They both are run through O(n*n) which is O(n^2)


c) O(n) returns O(1) + 0(n-1) in whiches it reduces to O(n)


## Exercise II

building, stories/floors = n
if eggs thrown off floor f or higher, then it's broken
elif egg thrown off floor less then f, then not broken 
else when on floor less then f, throw eggs otherwise don't throw...

O(n) If it's looping and going through the floors it's only throwing an egg when on floors less then f. 
