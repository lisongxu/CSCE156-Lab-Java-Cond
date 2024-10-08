# Computer Science II
## Lab 2.0 - Operators and Conditions

An introduction to the operators and conditions in the Java programming language.  

This is a lab used in Computer Science II (CSCE 156) for Fall 2024 
in the [School of Computing](https://computing.unl.edu) 
at the [University of Nebraska-Lincoln](https://www.unl.edu).

## Overview

### Resources

* `operator tutorial`:
https://docs.oracle.com/javase/tutorial/java/nutsandbolts/operators.html
* `if-else tutorial`:
http://download.oracle.com/javase/tutorial/java/nutsandbolts/if.html


### Lab Objectives & Topics
Following the lab, you should be able to:
* use operators, such as `+`, `-`, `*`, and `/`
* use `if-else` statements to control the logical flow of the
  program.

Note that the lab may involve some concepts, classes, or methods not covered (yet) in the class. You should be able to complete the lab without fully understanding them. If you have any questions about them, please feel free to ask our LAs. 

### Peer Programming Pair-Up

At the start of
each lab, you may find a team member by yourself or be randomly paired up with another student by
a lab instructor.  One of you will be designated the *driver* 
and the other is the *navigator*. Each week you should try to alternate: if you were a driver 
last week, be a navigator next, etc. If you prefer to work on this lab by yourself, that is fine too.

***Note that each student must submit the code to GradeScope for grading.***

## 1. Getting Started

Clone this project code for this lab from GitHub in Eclipse using the
URL: `https://github.com/lisongxu/CSCE156-Lab-Java-Cond`. Please refer to [Lab 1.0](https://github.com/lisongxu/CSCE156-Lab-Java-Intro) for
instructions on how to clone a project from GitHub in Eclipse.


## 2. Modifying the Statistics Java Programs

We continue to work on the Statistics Java programs. Note that the Statistics code in this lab is *different* from that of Lab 1, so you must clone the project code for this lab from GitHub.

Please modify `Statistics.java` as required below, so that `StatisticsDemo.java` outputs the correct answers. 

1. Expand the `src/main/java` directory, then expand the `unl.soc` package, and then double-click on the `Statistics.java` file to open it.
2. Implement the `getMax()` method in the `Statistics` class.  Use the 
`getMin()`	method for directions on syntax.
3. Implement the `getSum()` method in the `Statistics` class.  Use the 
other methods for direction on syntax.
4. Expand the `src/main/java` directory, expand the `unl.soc` package, and double-click on the `StatisticsDemo.java` file to open it.
5. Click on the "play" button to execute `StatisticsDemo.java`, and check the output in the "console" tab
 

## 3. Testing, Submitting, and Grading

### 3.1 Testing Locally

Before you submit your lab, you should run the JUnit tests locally to verify 
that your code is correct.  

1. Expand the `src/test/java` directory, then expand the `unl.soc` package, and then double-click on the `StatisiticsTests.java` file to open it.   
2. Run the test suite by clicking the usual "Play" button.
3. A report will be presented in a JUnit tab detailing which test cases pass and
which fail along with the expected output and the actual output (for 
failed test cases).

### 3.2 Submitting

To submit your lab, do the following. 

1. Go to Lab 2 on Canvas, and click the "Load Lab 2 in a new window" button which opens a GradeScope window for Lab 2.   

2. Drag and Drop your modified ***`Statistics.java`***, and then click the "Upload" button. ***Do not upload any other files.***

3. Wait for the website to grade your code, and make sure that you pass all tests. 

4. What if the test on GradeScope fails? Please test your program locally on your computer using the provided JUnit test suite, because the test on GradeScope is exactly the same as the provided JUnit test suite. ***Debugging your programs on GradeScope is not recommended because GradeScope gives very limited information.***

### 3.3 Grading

For this lab, as long as you pass all the tests on GradeScope, you will get full points for the lab.

