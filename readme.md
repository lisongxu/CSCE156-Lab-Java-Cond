# Computer Science II
## Lab 2.0 - Operators and Conditions

An introduction to the operators and conditions in the Java programming language.  

This is a lab used in Computer Science II (CSCE 156) for Fall 2023 
in the [School of Computing](https://computing.unl.edu) 
at the [University of Nebraska-Lincoln](https://unl.edu).

## Overview

### Lab Objectives & Topics
Following the lab, you should be able to:
* use operators, such as `+`, `-`, `*`, and `/`
* use `if-else` statements to control the logical flow of the
  program.

### Peer Programming Pair-Up

At the start of
each lab, you may find a team member by yourself or may be randomly paired up with another student by
a lab instructor.  One of you will be designated the *driver* 
and the other the *navigator*. If you prefer to work on this lab by yourself, that is fine too.  
Each week you should try to alternate: if you were a driver 
last week, be a navigator next, etc. 

***note that, each student must submit the code to CodePost for grading.***

## 1. Getting Started

Clone this project code for this lab from GitHub in Eclipse using the
URL: https://github.com/lisongxu/CSCE156-Lab-Java-Cond. Refer to [Lab 1.0](https://github.com/lisongxu/CSCE156-Lab-Java-Intro) for
instructions on how to clone a project from GitHub.


## 2. Modifying the Statistics Java Programs

The Statistics Java programs

All students should complete this Java section, even if you are 
already familiar with Java, in order to familiarize yourself 
with how labs will work for the semester.

Double click on the `StatisticsDemo` class to open it in the Eclipse 
editor.  This class contains a main method, `public static void main(String args[])`
In Java, classes are executable only if a main method is defined.  
Classes without a `main` method can be used by other classes, but 
they cannot be run by themselves as an entry point for the Java 
Virtual Machine (JVM).

Though the program runs, it does not output correct answers.  You 
will need to modify these classes to complete the program.

1. Implement the `getMax()` method in the `Statistics` class.  Use the 
`getMin()`	method for directions on syntax.
2. Implement the `getSum()` method in the `Statistics` class.  Use the 
other methods for direction on syntax.
3. Rerun the program to verify that it now works.

## 3. Testing and Submitting Your Lab

### 3.1 Testing Locally

Every lab will come with a collection of test files that contain 
a suite of *unit tests* using the JUnit testing framework.  Before
you submit your lab, you should run these tests locally to verify 
that your code is correct.  

1. Open the `StatisiticsTests.java` source file in the `src/test/java`
source folder.  This file contains several unit tests written using
JUnit *annotations*.  You are encouraged to explore how these tests
are written and work and to even add your own tests but otherwise, 
the file is complete.
2. Run the test suite by clicking the usual "Play" button.  A report
will be presented in a JUnit tab detailing which test cases pass and
which fail along with expected output and the actual output (for 
failed test cases).  

### 3.2 Submitting to CodePost

To submit your lab, do the following:

1. Login to <https://codepost.io>.  

2. Click "Upload Assignment" for this lab.

3. Click "Upload files" to upload the following required files, and then click the "Submit and run test" button.

* `Statistics.java`: You do not need to make any changes to this file, as this lab just shows you how CodePost works.
* `Birthday.java`: Please change variable names with underscores to the preferred lowerCamelCasing convention in Java.

4. Click on the "View test results" button to
view the test results, and make sure that you pass all tests. 


