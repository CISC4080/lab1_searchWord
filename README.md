# lab1_searchWord
In this lab, we practice solving two problems using brute-force strategy.

## Goal:

1. Keep practicing Python programming, 
2. Practicing step-wise refinement, checking boundary condition of loops
3. Testing functions with different testcases
4. Please review [this](https://python.pages.doc.ic.ac.uk/cpp/lessons/cpp/04-seq/07-strseq.html) to familarize yourself with **str** in Python. Essenntnially, a string (str) in Python is a list of char. 
   
## Preparation

1. Download the lab1.py.
2. Read this [article](https://realpython.com/python-main-function/) which descrbies **main** function in Python. 


## Overall requirements: 
   Please write comments for your functions: write comments before the function header to describe its funcionalities, its parameters and return value. 
   Write comments for keep parts of your function. 

## Detail Requirements:

We practice writing two functions to test whether a string is a substring of another string, and test whether a string is a subsequence of another string. 

The difference between substring and subsequence:  **substring** is a continuous part of a string, whereas **subsequence** is the part of a string , that might be continuous or not but the order of the elements is maintained.

For example, 

* "low" is a substring of "helloworld", and also a subsequence of "helloworld".
* while "how" is **NOT** a substring of "helloworld", but it **IS** a subsequence of "helloworld" (because it is part of "helloworld", but not a contiguous part of it).
* "oed" is not a substring, nor a subsequence of "helloworld" (although each of the characters o, e, d appears in "helloworld", the order of these chara is not maintained.). 
* empty string "" is a substring of any string.
* empty string "" is also a subsequence of any string.
  
1.  Implement a function **IsSubstring (str1, str2)**, which return True if **str2** is a substring of **str1**, and return False if it is not. 

Note that this is fundamentally the same as the **FindWord** function we worked on during in-class practice. 
   
3.  Implement a function **IsSubsequence (str1, str2)**, which returns True if **str2** is a subsequence of **str1**, return False if it is not.
5.  Test both of your functions in the **main**, you need to design at least four testcases for each functions.
   
## Submission

Submit your code named **lab1.py** on autograder site at the following link: 

TBA. 


  
