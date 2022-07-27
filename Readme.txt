--------------------------------------------------
[input frequency file format]
--------------------------------------------------
NSlots #Number of Slots
NTools #Number of Tools
NTools x NTools frequency matrix 
	[which is symmetric and has diagonal elements as zero.]
--------------------------------------------------
[example file content for NSlots=10, NTools=5]:
--------------------------------------------------
10
5
0 20 2 3 12
20 0 5 14 11
2 5 0 25 6
3 14 25 0 7 
12 11 6 7 0
--------------------------------------------------
[input starting sequence file format]
----------------------------------------------
NStarts #Number of stating solutions
Each subsequent line is a starting solution of length NTools
	[Each solution is composed of numbers 0 to NTools-1 arranged randomly in NTools positions] 
-----------------------------------------------
[Example file content for NStarts=3, NTools=10]:
-----------------------------------------------
3
2 0 5 4 3 7 9 1 8 6
8 0 2 7 3 9 2 4 6 5
7 3 2 4 0 5 8 6 9 1
------------------------------------------------



