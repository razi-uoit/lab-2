# Lab 2

This lab expects that you have already installed Dart SDK on your system and integrated it with Visual Studio Code. Although it is not necessary to have Dart SDK installed on your system and integrate it with Visual Studio Code but since instructor is going to use this combination throughout this course, it would be easier to follow. Having said that, you are free to use any editor (locally installed or online) to complete this lab.

## Instructions
Please read the instructions below carefully:
* This Lab has a weightage of **3%** marks of the course.
* This is NOT a group assignment so students having similar assignments will get a 0.
* You are required to submit the assignment on Canvas as instructed. Assignments through emails will not be accepted.

**Question 1**
---------------------

Write a program in Dart that checks to see if all the elements of the list are prime numbers or not? You are required to create a function `bool isPrime(List numbers)` that takes a list as a parameter and returns `true` if all the elements of the list are prime and returns `false` even if one of the elements is not prime. Please note the followings:
* List should be created in the main method
* `bool isPrime(List numbers)` method should use `forEach` method of list to run through each element of the list and finds if the element is prime or not.
* The output of the program should be `All elements of the list are Prime numbers` if elements are prime and `All elements of the list are Prime not numbers` if even one of the elements is not prime.

**Question 2**
---------------------
Write a program in Dart that checks to see if all the elements of the list are prime numbers or not just like what you did in Question 1 except, this time you are required to use a `map` function in dart? You can read about Dart map function on this link (https://api.dart.dev/stable/2.13.4/dart-core/Iterable/map.html ). 
Please note the followings:
* You can perform all the implementation in the main method
* Use map method to iterate through each element of the list. (Hint: look into toList() method as well.)
* The output of the program should be `All elements of the list are Prime numbers` if elements are prime and `All elements of the list are Prime not numbers` if even one of the elements is not prime.

**Question 3**
---------------------
Write a program in Dart that shows the usage of Classes. The program should have a class `SmartDevices` with the following members:
* String Brand 
* String OS 
* String Type 
* String Feature 
Furthermore, the class should have an overridden method `toString()` that should return a `String`.

Please note the followings:
* You need to create a short-form constructor for this class.
* Create two instances of this class in the `main` method which when printed should display the following respectively:
   1.	`Samsung Phone with Android operating system and makes calls.`
   2.	`Apple Tablet with iOS operating system and has big screen.`

* Please note that Samsung in instance 1 is Brand, Phone is Type, Android is OS and makes calls is Feature. Same applies to instance 2.

**Question 4**
---------------------
Write a program in Dart to demonstrate the usage of `mixins`. The program should have a class `Sportsman` that contains the method called `void isSportsman()`. Create two mixins, `Swimmer` and `Runner`. Each mixin should have a method `void iAmSwimmer()` with a print statement saying, `I am a swimmer` and `iAmRunner()` with a print statement saying, `I am a runner` respectively. 

Call these two mixin methods in `void isSportsman()` method of `Sportsman` class. Finally, in the `main` method, create an instance of `Sportsman` and call the `isSportsman` method to see if mixins are working with the class.
