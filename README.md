ThoughtWorks  Algorithm test： MazeFactory 
===================
Language：python2.73<br> 
How to use it：Open the ThoughtWorks.py file directly, run it<br> 
Unit test:
-----------
input:<br> 
3 3<br> 
0,1 0,2;0,0 1,0;0,1 1,1;0,2 1,2;1,0 1,1;1,1 1,2;1,1 2,1;1,2 2,2;2,0 2,1<br> 
output:<br> 
[W] [W] [W] [W] [W] [W] [W] <br> 
[W] [R] [W] [R] [R] [R] [W] <br> 
[W] [R] [W] [R] [W] [R] [W] <br> 
[W] [R] [R] [R] [R] [R] [W] <br> 
[W] [W] [W] [R] [W] [R] [W] <br> 
[W] [R] [R] [R] [W] [R] [W] <br> 
[W] [W] [W] [W] [W] [W] [W] <br> 
input:<br> 
3 3<br> 
0,1 0,2;0,0 1,0;0,1 1,1;0,2 1,2;1,0 1,1;1,1 1,2;1,1 2,1<br> 
output:<br> 
Maze format error.<br> 
input:<br> 
3 a<br> 
0,1 0,2;0,0 1,0;0,1 1,1;0,2 1,2;1,0 1,1;1,1 1,2;1,1 2,1<br> 
output:<br> 
Invalid number format.<br> 
input:<br> 
3 3<br> 
0,1 0,2;0,0 1,0;0,1 1,1;0,2 1,2;1,0 1,1;1,1 1,2;1,1 2,1;1,5 2,2;2,0 2,5<br> 
output:<br> 
Number out of range.<br> 
input:<br> 
3 3<br> 
0,1,0,2;0,0 1,0;0,1 1,1;0,2 1,2;1,0 1,1;1,1 1,2;1,1 2,1;1,0,2,2;2,0 2,1<br> 
output:<br> 
Incorrect command format<br> 
