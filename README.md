ThoughtWorks  Algorithm test： MazeFactory<br> 
===================
Language：python2.73<br> 
How to use it：Open the ThoughtWorks.py file directly, run it<br> 
Unit test:<br> 
input:<br> 
`"
3 3
0,1 0,2;0,0 1,0;0,1 1,1;0,2 1,2;1,0 1,1;1,1 1,2;1,1 2,1;1,2 2,2;2,0 2,1
`"
output:<br> 
`"
[W] [W] [W] [W] [W] [W] [W] 
[W] [R] [W] [R] [R] [R] [W] 
[W] [R] [W] [R] [W] [R] [W] 
[W] [R] [R] [R] [R] [R] [W] 
[W] [W] [W] [R] [W] [R] [W] 
[W] [R] [R] [R] [W] [R] [W] 
[W] [W] [W] [W] [W] [W] [W] 
`"
input:<br> 
`"
3 3
0,1 0,2;0,0 1,0;0,1 1,1;0,2 1,2;1,0 1,1;1,1 1,2;1,1 2,1
`"
output:<br> 
`"
Maze format error.
`"
input:<br> 
`"
3 a
0,1 0,2;0,0 1,0;0,1 1,1;0,2 1,2;1,0 1,1;1,1 1,2;1,1 2,1
`"
output:<br> 
`"
Invalid number format.
`"
input:<br> 
`"
3 3
0,1 0,2;0,0 1,0;0,1 1,1;0,2 1,2;1,0 1,1;1,1 1,2;1,1 2,1;1,5 2,2;2,0 2,5
`"
output:<br> 
`"
Number out of range.
`"
input:<br> 
`"
3 3
0,1,0,2;0,0 1,0;0,1 1,1;0,2 1,2;1,0 1,1;1,1 1,2;1,1 2,1;1,0,2,2;2,0 2,1
`"
output:<br> 
`"
Incorrect command format
`"
