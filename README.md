1. We can express insertion sort as a recursive procedure. Please write the pseudo-code for insertion sort in a recursive fashion and provide the recurrence of the runnung time.

2. Althought merge sort runs in ![image](https://github.com/jysh1214/ntut_algorithm2018/blob/master/image/CodeCogsEqn.gif) worst-case time and insertion sort runs in ![image](https://github.com/jysh1214/ntut_algorithm2018/blob/master/image/CodeCogsEqn_1.gif) worst-case time, the constant factors in insertion sort can make it faster in practice for small problem sizes on many machines. Thus, it makes sense to coarsen the leaves of the recursion by using insertion sort within merge sort in with ![image](https://github.com/jysh1214/ntut_algorithm2018/blob/master/image/CodeCogsEqn_2.gif) sublists of length ![image](https://github.com/jysh1214/ntut_algorithm2018/blob/master/image/CodeCogsEqn_3.gif) are sorted using insertion sort and then merge using the standard mergeing mechanism, where ![image](https://github.com/jysh1214/ntut_algorithm2018/blob/master/image/CodeCogsEqn_3.gif) is a value to be determined.

  - (a) Show that insertion sort can sort the ![image](https://github.com/jysh1214/ntut_algorithm2018/blob/master/image/CodeCogsEqn_2.gif) sublists, each of length ![image](https://github.com/jysh1214/ntut_algorithm2018/blob/master/image/CodeCogsEqn_3.gif), in ![image](https://github.com/jysh1214/ntut_algorithm2018/blob/master/image/CodeCogsEqn_4.gif) worst-case time.
  
  - (b) Show how to merge the sublists in ![image](https://github.com/jysh1214/ntut_algorithm2018/blob/master/image/CodeCogsEqn_5.gif) worst-case time.
  
  - (c) Given that the modified algorithm runs in ![image](https://github.com/jysh1214/ntut_algorithm2018/blob/master/image/CodeCogsEqn_6.gif) worst-case time, what is the largest value of ![image](https://github.com/jysh1214/ntut_algorithm2018/blob/master/image/CodeCogsEqn_3.gif) as a function of ![image](https://github.com/jysh1214/ntut_algorithm2018/blob/master/image/CodeCogsEqn_7.gif) for which the modified algorithm has the same runnung time as standard merge sortr, in terms of ![image](https://github.com/jysh1214/ntut_algorithm2018/blob/master/image/CodeCogsEqn_8.gif)-notation.
  
  - (d) How should we choose ![image](https://github.com/jysh1214/ntut_algorithm2018/blob/master/image/CodeCogsEqn_3.gif) in practice?

3. Please verify the following statements. If it is true, please show it; otherwise, give an argument to show the incorrectness.
    
    (a) ![image](https://github.com/jysh1214/ntut_algorithm2018/blob/master/image/3-1.gif)
    
    (b) ![image](https://github.com/jysh1214/ntut_algorithm2018/blob/master/image/3-2.gif)
    
4. We can extend the notation to the case of two parameters n and m that can go to infinity independently at different rates. For a given function ![image](https://github.com/jysh1214/ntut_algorithm2018/blob/master/image/4-1.gif)![image](https://github.com/jysh1214/ntut_algorithm2018/blob/master/image/4-2.gif) the set of functions

  ![image](https://github.com/jysh1214/ntut_algorithm2018/blob/master/image/4-2.gif) = {f(n, m) : there exit positive constants c, n0, and m0 such that 0 <=f(n, m) <= c*g(n, m) for all n >= n0 or m >= m0}.

  Give corresponding definitions for ![image](https://github.com/jysh1214/ntut_algorithm2018/blob/master/image/4-3.gif) and ![image](https://github.com/jysh1214/ntut_algorithm2018/blob/master/image/4-4.gif).
  
5.Design an algorithm for computing ![image](https://github.com/jysh1214/ntut_algorithm2018/blob/master/image/5-1.gif) for any positive integer n. Besides assignment and comparsion, your algorithm may only use the four basic arithmetical operations. In your answer, you first describe the idea (approach) and then the pseudo-code. Further-more, please give a short explanation to claim that your algorithm is correct and what the time complexity of your algorithm is.
