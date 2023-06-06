# Lab Report 5

## Part 1 - Debugging Scenario
1) original post from student:

**What environment are you using (computer, operating system, web browser, terminal/editor, and so on)?**

I am operating on a MacBook Pro that has an operating system of MacOS and I am using the terminal in VSCode. 

**Detail the symptom you're seeing. Be specific; include both what you're seeing and what you expected to see instead. Screenshots are great, copy-pasted terminal output is also great. Avoid saying “it doesn't work”.**

Two of my tests are failing and the length of the expected array is different from the length of the actual array. In addition, the elements in the arrays are not entirely correct. In testMerge2, the expected array is { "a", "b", "c", "d", "e" }, but the actual array is { "a", "b", "d", "e" }. In testMerge3, the expected array is { "a", "b", "c", "d", "e" }, but the actual array is {"b", "c", "d", "e" }. These two tests have duplicates in them, so I think that might be the problem since none of the elements that were a duplicate appear in the final array. 

![Image](studentogpost3-2.png)

**Detail the failure-inducing input and context. That might mean any or all of the command you're running, a test case, command-line arguments, working directory, even the last few commands you ran. Do your best to provide as much context as you can.**

The failure-inducing inputs are testMerge2 and testMerge3 in the ListExamplesTests.java file: ![Image](studentogpost2.png)
This is my code in the ListExamples.java file: ![Image](studentogpost1.png)
This is my test.sh file: ![Image](studentogpost4.png)
The only command that I am running is bash test.sh in order to run the tests. 

2) response from a TA:



3) student applying feedback and a clear description of what the bug is:
4) all information about the setup:

## Part 2 - Reflection 
