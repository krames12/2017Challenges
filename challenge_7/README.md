Find The Missing Number
======
Idea
------
Given a list of numbers from 0 to N-1, your job is to find the missing number. Your program should take in a list of integers and return a single integer (the missing number).

Note: This is a popular interview question. Bloomberg in particular, really likes this question. 

Input
-----
* The list of integers will not be sorted
* Each value in the list will be between 0 and N
* Each value will only appear once in the list
* Only one number will be missing

Requirements
------------
* You should not sort the list of integers
* Your solution should use O(1) space and complete in O(N) time
* O(1) space means that your algorithm should not need to allocate an additional additional array of N elements to solve the problem
* O(N) times means that your algorithm can not contain nested loops

Notes
-----
* The test cases will not be sorted
* The fact that the values range from 0 to N is important

Example 1
---------
Given the list [0,1,2,4], your program should return the number 3

Example 2
---------
Given the list [1,2,3], your program should return the 0.

Testing
------
Testing for this challenge is fairly straight forward. Simply create a list of
size N, filled with integers from 0 to N, with one integer missing.

For example:

```ruby
assert findMissing([1,3,4,0]) == 2
```
