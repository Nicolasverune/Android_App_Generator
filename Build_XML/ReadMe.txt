ONLY EDIT : Questions.txt

Questions.txt is the file to change the questions and generate xml/java files
For now only generates radiogroup questions and the button at the end of the page

Syntax : 

Question
Answer1$Depression$Anxiety
ANswer2$Depression$Anxiety
..

--  = New Question

--- = New Xml file

----- = End of the questions

Attention : 
	-Don't put any space character, especialy in "-" lines
	-Don't jump any lines

To execute on linux, cd to this directory, then: 

java -jar QuestionsToXML.jar
