# hello-world

Problem #1: 

a) Selection Sort: M U E J R Q X B
M U E J R Q X B
B U E J R Q X M
B E U J R Q X M
B E J U R Q X M
B E J M R Q X U
B E J M Q R X U

b) Insertion Sort: M U E J R Q X B
M U E J R Q X B
E M U J R Q X B
E J M U R Q X B
E J M R U Q X B
E J M R Q U X B
B E J M R Q U X 

---

Problem #2:

A) Determine if 2 arrays contain the same elements

1) Check if both arrays have equal length
   Compare each element in array one to array two
   Check if the number of elements is equal in array one and array two until the length is reached

2) n represents length of the arrays and x represents the elements being compared to each other

3) The operations to be counted are the comparing of the elements between the two arrays

4) f(n) = (n^2)

5) Best Case: O(1)
   Worst Case: O(n^2)
   Efficiency analysis: Input Size: length of both arrays
   			What to Count: comparison of number of elements
   			Big O(n^2)
   
6) Big O(n^2) 


B) Counting total number characters that have a duplicate within a string (i.e. "gigi the gato" would result in 7 (g x 3 + i x 2 + t x 2)

1) Loop through the length of the string to check each char
   Compare each of the chars  
   If the char at index i is the same as another char within the string, increment the counter for the number of that char 

2) n represents the length of the string and x represents the chars being compared to each other

3) The operations to be counted are the comparisons of the chars checking if it is the same as another char

4) f(n) = (n(n-1)/2)

5) Best Case: O(n)
   Worst Case: O(n^2)
   Efficiency analysis: Input Size: length of String
   What to Count: comparisons of chars
   Big O(n^2)

6) Big O(n^2)


C) Finding an empty row in a 2-D array where empty is defined as an element with a 0 entry.

1) Loop through the rows and columns of the array
   Compare the elements in the row and column at index i
   Check if the elements are both equal to 0

2) n represents the length of the row, p represents the length of the column, and x represents the comparisons between the elements in the row and column

3) The operations to be counted are the comparisons between the elements in the row and column to check if they contain a 0

4) f(n) = (np + x)  

5) Best Case: O(n)
   Worst Case: O(np)
   Efficiency analysis: Input Size: length of row and column
  What to Count: comparisons between elements in the row and column
	Big O(np)

6) Big O(np)
