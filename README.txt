hadoop
======
Setting up and running hadoop to run MapReduce applications. 

***BiWordCount.java is a simple modification of WordCount.java to count the occurences of adjacent words in a text file, rather than just the single words.

***Sopa.htm- Sample input file

*** How to compile and run:

--$javac -classpath *:lib/* -d biwordcount_classes BiWordCount.java

--$jar -cvf biwordcount.jar -C biwordcount_classes/ .

--$bin/hadoop jar biwordcount.jar BiWordCount <input file> <output file>
