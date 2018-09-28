# 1. We can express insertion sort as a recursive procedure. Please write the pseudo-code for insertion sort in a recursive fashion and provide the recurrence of the runnung time.

# 2. Althought merge sort runs in ![image](https://github.com/jysh1214/ntut_algorithm2018/blob/master/image/CodeCogsEqn.gif) worst-case time and insertion sort runs in ![image](https://github.com/jysh1214/ntut_algorithm2018/blob/master/image/CodeCogsEqn_1.gif) worst-case time, the constant factors in insertion sort can make it faster in practice for small problem sizes on many machines. Thus, it makes sense to coarsen the leaves of the recursion by using insertion sort within merge sort in with ![image](https://github.com/jysh1214/ntut_algorithm2018/blob/master/image/CodeCogsEqn_2.gif) sublists of length ![image](https://github.com/jysh1214/ntut_algorithm2018/blob/master/image/CodeCogsEqn_3.gif) are sorted using insertion sort and then merge using the standard mergeing mechanism, where ![image](https://github.com/jysh1214/ntut_algorithm2018/blob/master/image/CodeCogsEqn_3.gif) is a value to be determined.

  - (a) Show that insertion sort can sort the ![image](https://github.com/jysh1214/ntut_algorithm2018/blob/master/image/CodeCogsEqn_2.gif) sublists, each of length ![image](https://github.com/jysh1214/ntut_algorithm2018/blob/master/image/CodeCogsEqn_3.gif), in ![image](https://github.com/jysh1214/ntut_algorithm2018/blob/master/image/CodeCogsEqn_4.gif) worst-case time.
  
  - (b) Show how to merge the sublists in ![image](https://github.com/jysh1214/ntut_algorithm2018/blob/master/image/CodeCogsEqn_5.gif) worst-case time.
  
  - (c) Given that the modified algorithm runs in ![image](https://github.com/jysh1214/ntut_algorithm2018/blob/master/image/CodeCogsEqn_6.gif) worst-case time, what is the largest value of ![image](https://github.com/jysh1214/ntut_algorithm2018/blob/master/image/CodeCogsEqn_3.gif) as a function of ![image](https://github.com/jysh1214/ntut_algorithm2018/blob/master/image/CodeCogsEqn_7.gif) for which the modified algorithm has the same runnung time as standard merge sortr, in terms of ![image](https://github.com/jysh1214/ntut_algorithm2018/blob/master/image/CodeCogsEqn_8.gif)-notation.
  
  - (d) How should we choose ![image](https://github.com/jysh1214/ntut_algorithm2018/blob/master/image/CodeCogsEqn_3.gif) in practice?
