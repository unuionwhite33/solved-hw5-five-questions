Download Link: https://assignmentchef.com/product/solved-hw5-five-questions
<br>
Do not minimize. The grader has only the plain answers.

<ol>

 <li>Write two VHDL statements that implement the truth table below Just use  “and”   “or”   and  “not”  with parenthesis.  the answer starts   x &lt;=</li>

</ol>

y &lt;=




a b c | x y

——+—-

0 0 0 | 0 0

0 0 1 | 1 1

0 1 0 | 0 0

0 1 1 | 0 1

1 0 0 | 1 0

1 0 1 | 0 1

1 1 0 | 1 0

1 1 1 | 0 0




<a href="http://userpages.umbc.edu/~squire/images/cs411_l3a.pdf">Use this style, do not minimize.</a>




<ol start="2">

 <li>Write the VHDL statement that implements the logic diagram</li>

</ol>




+—-


a –|OR  |____

b –|    |   |

+—-+   | +—-


–|NAND|

+—-+     |    |

c –|NOR |_____|    |__

d –|    |     |    |  |

+—-+     |    |  |

–|    |  |

+—-+   | |    |  |

e –|NOT |—| +—-+  |  +—-


+—-+             |–| OR |

|    |– g

f ————————|    |

+—-





Be sure to include the semicolon in VHDL statements,

else you lose one point for each that is missing.




<ol start="3">

 <li>Draw the logic diagram that represents the VHDL statement</li>

</ol>




g &lt;= ((not a and b) xor (c or not d or e)) or (f and not e);




<ol start="4">

 <li>For the following schematic, Ripple Carry wiring:</li>

</ol>

Use a, b, e and f  all as four ones. e.g. a &lt;= “1111”   etc.

4a) what is the six bit result s.

4b) given that the time from any input to any output in the

full adder is  2T, how much time does the longest path from

any input to any output require?   the answer is   ____ T










<ol start="5">

 <li>For the following schematic, Carry Save wiring:</li>

</ol>

Use a, b, e and f  all as four ones. e.g. a &lt;= “1111”   etc.

5a) what is the six bit result s.

5b) given that the time from any input to any output in the

full adder is  2T, how much time does the longest path from

any input to any output require?   the answer is   ____ T


