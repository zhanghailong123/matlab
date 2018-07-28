ThoughtWorks  Algorithm test： MazeFactory
===================
Language：python2.73
How to use it：Open the ThoughtWorks.py file directly, run it
Unit test:
input:
3 3
0,1 0,2;0,0 1,0;0,1 1,1;0,2 1,2;1,0 1,1;1,1 1,2;1,1 2,1;1,2 2,2;2,0 2,1
output:
[W] [W] [W] [W] [W] [W] [W] 
[W] [R] [W] [R] [R] [R] [W] 
[W] [R] [W] [R] [W] [R] [W] 
[W] [R] [R] [R] [R] [R] [W] 
[W] [W] [W] [R] [W] [R] [W] 
[W] [R] [R] [R] [W] [R] [W] 
[W] [W] [W] [W] [W] [W] [W] 

input:
3 3
0,1 0,2;0,0 1,0;0,1 1,1;0,2 1,2;1,0 1,1;1,1 1,2;1,1 2,1
output:
Maze format error.

input:
3 a
0,1 0,2;0,0 1,0;0,1 1,1;0,2 1,2;1,0 1,1;1,1 1,2;1,1 2,1
output:
Invalid number format.

input:
3 3
0,1 0,2;0,0 1,0;0,1 1,1;0,2 1,2;1,0 1,1;1,1 1,2;1,1 2,1;1,5 2,2;2,0 2,5
output:
Number out of range.

input:
3 3
0,1,0,2;0,0 1,0;0,1 1,1;0,2 1,2;1,0 1,1;1,1 1,2;1,1 2,1;1,0,2,2;2,0 2,1
output:
Incorrect command format
