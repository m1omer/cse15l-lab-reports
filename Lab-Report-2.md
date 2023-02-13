
# Lab Report 2

__Part 1__

![image](https://user-images.githubusercontent.com/122564032/215642634-b5269cba-995b-441c-9050-77bfa89e3a93.png)
When add message is used in this instance, the handleRequest method is called. The URI "localhost:2100/add-message?s=my phone is about to die" is passed into the handlerRequest method using the variable url. The method then breaks the url at the "=" sign and then stores the resulting strings into an array called parameters. After which the phrase "my phone is about to die" is saved in a variable called userInput. The variable userInput is a string which contains all the previously entered strings in the url. Therefore, when handleRequest returns userInput the previously entered strings are also visible.

![image](https://user-images.githubusercontent.com/122564032/215642688-25fbc35e-f168-4048-bbfb-b0ad4345e9bb.png)
In this instance when I used add message to enter "bye then", the handleRequest method was also called. The URI "localhost:2100/add-message?s=bye%20then" is passed into the handlerRequest method using the variable url. The method then used the same process as mentioned above to return all the previous strings entered as well as "bye then".


<img width="1512" alt="Screen Shot 2023-01-30 at 6 11 35 PM" src="https://user-images.githubusercontent.com/122564032/215642714-43f383f3-502b-4885-930a-452ff89fc925.png">


__Part 2__

A failure-inducing input for the buggy program, as a JUnit test
```java
{
public class ArrayTests {
	@Test 
	public void testReverseInPlace() {
    int[] input1 = { 3, 2, 4 };
    ArrayExamples.reverseInPlace(input1);
    assertArrayEquals(new int[]{ 4,2,3 }, input1);
	}
}
```

An input which doesn't induce failure 

```java
{
public class ArrayTests {
	@Test 
	public void testReverseInPlace() {
    int[] input1 = {21};
    ArrayExamples.reverseInPlace(input1);
    assertArrayEquals(new int[]{21}, input1);
	}
}
```
<img width="987" alt="Screen Shot 2023-01-30 at 11 51 20 PM" src="https://user-images.githubusercontent.com/122564032/215699051-d31aafbc-0dc8-4807-822d-cace5bef8374.png">


Code before the change 

```java

  static void reverseInPlace(int[] arr) {
    int[] arr1 = new int[arr.length];
    for(int i = 0; i < arr.length; i += 1) {
      arr[i] = arr[arr.length - i - 1];
      arr1[i] = arr[arr.length - i - 1];
    }
  }
```

Code after the change

```java
  static void reverseInPlace(int[] arr) {
    int[] arr1 = new int[arr.length];
    for(int i = 0; i < arr.length; i += 1) {
      arr1[i] = arr[arr.length - i - 1];
    }
    arr = arr1;
  }
``` 

This code now works as it prevents the elements at the start from being reassigned by storing all the elements from the input array in a new arrray arr1. Then the reference for arr is assigned to arr1 which contains the elements in the reverse order. In the previous iteration of the code, the array entered by the user was being rewritten, hence the bug. 

__Part 3__
One thing I learned from week 2 and 3 was how to set up my own local server and run commands on it. Previously I had only known about accessing existing servers remotely. 

