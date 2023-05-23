# Lab Report 4

## Step 4: Log into ieng6
![Image](step4.png)

Keys pressed: ```ssh cs15lsp23pi@ieng6.ucsd.edu``` <enter> 

I ssh-ed into the remote server with my course specific account.

## Step 5: Clone your fork of the repository from your Github account
![Image](step5redo.png) 

Keys pressed: ```git clone https://github.com/ege915/lab7.git``` <enter>

## Step 6: Run the tests, demonstrating that they fail
![Image](step6.png)

Keys pressed: ```cd lab7``` <enter> ```javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java``` <enter> ```java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ArrayTests``` <enter>

## Step 7: Edit the code file to fix the failing test
![Image](step7.png)

Keys pressed: ```vim Li``` <tab> ```.java``` <enter> ```/while(index2``` <enter> ```jjjexi2```<esc> ```:wq``` <enter> 


## Step 8: Run the tests, demonstrating that they now succeed
![Image](step8.png)

Keys pressed: ```bash t``` <tab> <enter>

## Step 9: Commit and push the resulting change to your Github account (you can pick any commit message!)
![Image](step9-1.png)
![Image](step9-2.png)

Keys pressed: ```git init``` <enter> ```git add L``` <tab> ```.java``` <enter> ```git commit -m "edited files"``` <enter> 








For each numbered step starting right after the timer (so steps 4-9), take a screenshot, and write down exactly which keys you pressed to get to that step. For special characters like <enter> or <tab>, write them in angle brackets with code formatting. Then, summarize the commands you ran and what the effect of those keypresses were.

For example, when you run the tests, you might want to use the up arrow or Ctrl-R to access your bash history rather than typing in the full command with classpath, etc. You might say something like this accompanying the screenshot for running the tests:

Keys pressed: <up><up><up><up><enter>, <up><up><up><up><enter> The javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java command was 4 up in the search history, so I used up arrow to access it. Then the java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ... command was 4 up in the history, so I accessed and ran it in the same way.


  
