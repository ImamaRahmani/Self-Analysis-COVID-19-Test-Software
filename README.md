# Self-Analysis-COVID-19-Test-Software
The project is specifically designed for institutes, in order to keep the COVID-19 result status and make students and teachers aware about their situation. The software asks the user’s general data, like name, age, blood group and vaccination information. Afterwards, user is asked 5 questions. As the user answers the questions, a report is formulated using the input data and a record is saved whether the user is COVID-19 positive or COVID-19 negative. 

•	Solution Approach:
Using binary tree data structure to make a structured questionnaire through which program can conclude the result. Using nested if-else command to approach next possible nodes and decision. The program uses the techniques for decision making without involving AI/ML Modules.(Mimicking AI)

•	Project Features:
Operating System: Windows
IDE(s): VS Code and Visual Studio Community 2019
Data Structure: Binary Tree
Programming Language: Python
Number of code lines: 349

•	Data Structure:
A Binary Tree starts with a root node. The nodes holds the questions and the edges of the binary tree serve as conditions, leading to the next possible node(question). And the leaf nodes hold the result. Due to nested structure of our project, we have used  Binary Tree.

•	Time Complexity:
o	The time complexity of going from one question to another is O(1).
o	The time complexity of starting the questionnaire till the result is shown is O(n).

•	Algorithm:
o	Node1 = Are you experiencing COVID-19 symptoms?
o	Node2 = Which are you?
o	Node3 = Did your result recommend a follow up test?
o	Node4 = Is your test positive?
o	Node5 = Have you had close contact with someone who's tested positive?
o	RN1 = >>> Result: Positive
o	RN2 = >>> Result: Negative  

If Node1 == Yes:
If Node2 == Student:
If Node4 == Yes:
Then, Print RN1
                                        Elif Node4 == No:
If Node5 == Yes:
Then, Print RN2
	Elif Node5 == No:
 	Then, Print RN2
  Elif Node2 == Teacher:
 	If Node4 == Yes:
	Then, Print RN1
Elif Node4 == No:
	If Node5 == Yes:
 	Then, Print RN2
	Elif Node5 == No:
 	Then, Print RN2
Elif Node1 == No:
If Node3 == Yes:
If Node2 == Student:
If Node4 == Yes:
Then, Print RN1
Elif Node4 == No:
If Node5 == Yes:
Then, Print RN2
Elif Node5 == No:
Then, Print RN2
Elif Node2 == Teacher:
If Node4 == Yes:
Then, Print RN1
Elif Node4 == No:
If Node5 == Yes:
Then, Print RN2
Elif Node5 == No:
Then, Print RN2
Elif Node3 == No:
If Node5== Yes:
If Node2 == Student:
Then, Print RN1
Elif Node2 == Teacher:
Then, Print RN1
Elif Node5 == No:
Then, Print RN2

•	Screenshots:
 
General Data Input

 
Questionnaire 

 
Report

 
Time calculation for analyzing time complexity


•	Applications:
o	This software can be used to analyze the COVID-19 status of each person in any sector such as:
	Universities
	Offices
	Public Places
	Home
o	We can alternate the program in such a way that we can create software for  decision making and questionnaire.

•	Future upgradations:
File handling can be implemented to save record permanently. Secondly, AI Decision Tree can be implemented in future upgradation for analyzing the data of mass number of users. This can be used to analyze the COVID-19 positivity ratio in a specific region and makes decision making easier for administration.




