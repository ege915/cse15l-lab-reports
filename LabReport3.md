# Lab Report 3

## less -N 
**example1**:
  
command: ```less -N technical/government/Media/A_helping_hand.txt```
  
output: 

![Image](option1-1.png)

**example2**: 

command: ```less -N technical/911report/chapter-8.txt```

output:

![Image](option1-2.png)

**explanation**: less -N numbers each line in the file. For example, there will be a 1 next to the first line in the file, 2 next to the second line in the file, and so on. This is useful because it allows you to find a specific line quickly without having to skim through the whole file. An example of this could be if Person A and Person B are having a discussion about one of the .txt files and Person A wants Person B to look at line 159 of the file. Person A could then tell Person B to use less -N <<file>> and Command+F "159" to easily find what line 159 says. 
  
**citation**: I found this command-line option by using the built in command ```man less```.
  

## less -s
**example1**:
  
command: ```less -s technical/government/Alcohol_Problems/Session2-PDF.txt```
  
output: 
  
![Image](option2-1.png)

**example2**: 

command: ```less -s technical/government/Alcohol_Problems/DraftRecom-PDF.txt```

output:
  
![Image](option2-2.png)

**explanation**: less -s consolidates consecutive blank lines into a single blank line. This is useful because if a file has a lot of consecutive blank lines, you can combine them into just one blank line so that you don't have to scroll as much. 
  
**citation**: I found this command-line option by using the built in command ```man less```.
  

## less -m
**example1**:
  
command: ```less -m technical/biomed/rr74.txt```
  
output: 
  
![Image](option3-1.png)

**example2**: 

command: ```less -m technical/plos/pmed.0020015.txt```

output:
  
![Image](option3-2.png)

**explanation**: less -m allows you to see what percent of the file you have looked at or in other words shows a percent of how far into the file you are. This is useful because it could help you determine how much of the file you have left to read.
  
**citation**: I found this command-line option by using the built in command ```man less```.


## less -N 
**example1**:
  
command: 
  
output: 
  
![Image](option4-1.png)

**example2**: 

command: 

output:
  
![Image](option4-2.png)

**explanation**: 
  
**citation**: I found this command-line option by using the built in command ```man less```.



For each of those options, give 2 examples of using it on files and directories from ./technical. Show each example as a code block that shows the command and its output, and write a sentence or two about what it’s doing and why it’s useful. That makes 8 total examples, all focused on a single command. There should be two examples each for four different command-line options. 


