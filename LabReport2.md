# Lab Report 1

## Part 1
![Image](addMessage1.png)
* The methods that are called are the handleRequest method in the **Handler** class and the main method in the **StringServer** class.
* The relevant argument for the handleRequest method is a url of type URI and the relevant argument for the main method is the port number. As for the values of any relevant fields, the **Handler** class has a field called **str** of type String, while the **StringServer** class doesn't have any relevant fields.
* The value of **str** changes from this specific request because it changes from an empty string "" to "Hello" and a new concatenated line. 

![Image](addMessage2.png)
* The methods that are called are the handleRequest method in the **Handler** class and the main method in the **StringServer** class.
* The relevant argument for the handleRequest method is a url of type URI and the relevant argument for the main method is the port number. As for the values of any relevant fields, the **Handler** class has a field called **str** of type String, while the **StringServer** class doesn't have any relevant fields.
* The value of **str** changes from this specific request because it changes from "Hello" and a new concatenated line to "Hello", "How are you" in a new line, and a new concatenated line. 

## Part 2
```
public class ArrayTests{
  @Test
  public void testReversedArray(){
  int[] input = {1, 2, 3, 4};
  int[] output = {4, 3, 2, 1};
  assertArrayEquals(output, ArrayExamples.reversed(input));
  }
}
```

## Part 3
