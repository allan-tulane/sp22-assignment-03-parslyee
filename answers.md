# CMPS 2200 Assignment 3
## Answers

**Name:**Lily Yee


Place all written answers from `assignment-03.md` here for easier grading.



- **b.**

The work is W(n) = O(n) and the span is S(n) = O(n).


- **d.**

For this solution, we know that map has O(n) work and O(1) span, scan has O(n) work and (Olgn) span, and reduce has O(n) work and O(lgn) span. We can combine these to find that this solution has O(n) work and O(lgn) span. 


- **f.**

The work for this solution is W(n) = 2W(n/2) + 1, which has a leaf dominated tree. Its Big Oh solution is O(n). 

The span for this solution is S(n) = S(n/2) + 1, which has a balanced tree. Its Big Oh solution is O(lgn). 
