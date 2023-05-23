Log into ieng6  
2 up  
enter  
  

Clone your fork of the repository from your Github account  
control + r  
then type 'git'   
was the first result of reverse search, git clone https://github.com/mjcdeleon/lab7.gi
t  
control + r cd lab7

Run the tests, demonstrating that they fail  
control + r  
then type 'javac'
was the first result of reverse search, javac ListExamples.java ListExamplesTests.java  



Edit the code file to fix the failing test  
vim ListExamples.java  
6 up 
11 right  
x key  
i key  
2  
changed the 1 to a 2  


Run the tests, demonstrating that they now succeed  
javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java  
java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests  
Now show screenshot

