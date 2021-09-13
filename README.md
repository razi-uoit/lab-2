# Lab 2

This lab expects that you have already installed Dart SDK on your system and integrated it with Visual Studio Code. Although it is not necessary to have Dart SDK installed on your system and integrate it with Visual Studio Code but since instructor is going to use this combination throughout this course, it would be easier to follow. Having said that, you are free to use any editor (locally installed or online) to complete this lab.

## Instructions
In order to obtain maximum marks in this assignment, please ensure the followings:
* This Lab has a weightage of 3% marks of the course.
* This is NOT a group assignment so students having similar assignments will get a 0.
* You are required to submit the assignment on Canvas as instructed. Assignments through emails will not be accepted.

**Question 1**
___________________________

Write a program in Dart that checks to see if all the elements of the list are prime numbers or not? You are required to create a function `bool isPrime(List numbers)` that takes a list as a parameter and returns `true` if all the elements of the list are prime and returns `false` even if one of the elements is not prime. Please note the followings:
* List should be created in the main method
* `bool isPrime(List numbers)` method should use `forEach` method of list to run through each element of the list and finds if the element is prime or not.
* The output of the program should be `All elements of the list are Prime numbers` if elements are prime and `All elements of the list are Prime not numbers` if even one of the elements is not prime.

**Question 2**
____________
Write a program in Dart that checks to see if all the elements of the list are prime numbers or not just like what you did in Question 1 except, this time you are required to use a `map` function in dart? You can read about Dart map function on this link (https://api.dart.dev/stable/2.13.4/dart-core/Iterable/map.html ). 
Please note the followings:
* You can perform all the implementation in the main method
* Use map method to iterate through each element of the list. (Hint: look into toList() method as well.)
* The output of the program should be `All elements of the list are Prime numbers` if elements are prime and `All elements of the list are Prime not numbers` if even one of the elements is not prime.
