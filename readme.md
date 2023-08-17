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

To encourage collaboration and a team environment, labs will be
structured in a *pair programming* setup.  At the start of
each lab, you may find a team member by yourself or may be randomly paired up with another student by
a lab instructor.  One of you will be designated the *driver* 
and the other the *navigator*. If you prefer to work on this lab by yourself, that is fine too.  

The navigator will be responsible for reading the instructions 
and telling the driver what is to be done.  The driver will be 
in charge of the keyboard and workstation.  Both driver and 
navigator are responsible for suggesting fixes and solutions 
*together*.  Neither the navigator nor the driver is "in charge."  
Beyond your immediate pairing, you are encouraged to help and 
interact and with other pairs in the lab.

Each week you should try to alternate: if you were a driver 
last week, be a navigator next, etc.  Resolve any issues (you 
were both drivers last week) within your pair.  Ask the lab 
instructor to resolve issues only when you cannot come to a 
consensus.  

***note that, each student must submit the code to CodePost for grading.***

## 1. Getting Started

Clone this project code for this lab from GitHub in Eclipse using the
URL: https://github.com/lisongxu/CSCE156-Lab-Java-Cond. Refer to [Lab 1.0](https://github.com/lisongxu/CSCE156-Lab-Java-Intro) for
instructions on how to clone a project from GitHub.


## 3. Running Java Programs

All students should complete this Java section, even if you are 
already familiar with Java, in order to familiarize yourself 
with how labs will work for the semester.

### 3.1. Running a Program

We will now familiarize you with Eclipse by running an existing
project's code.

1. Expand the `src` directory.  Under this we have a *package* named 
`unl.soc`.  Java classes are organized in a hierarchy of packages.
Packages correspond to actual directories in your file system.  

2. Expand the package and you'll find several *classes*.	All Java code 
must be contained in a class.  This is in contrast to other languages 
that may allow global variables or allow functions to exist without an 
object or a class.

3. Double click on the `StatisticsDemo` class to open it in the Eclipse 
editor.  This class contains a main method, `public static void main(String args[])`
In Java, classes are executable only if a main method is defined.  
Classes without a `main` method can be used by other classes, but 
they cannot be run by themselves as an entry point for the Java 
Virtual Machine (JVM).

4. Click on the "play" button as highlighted. Note that please click "Proceed" in the "Errors in Workspace" window that will be fixed in the next step. 
<p align="center">
<img src="images/eclipseScreen-Xu.png" alt="Eclipse Screen" width="70%"/>
</p>
5. The output for this program will appear in the "console" tab at the bottom.
6. Click on the console tab and enter the input as specified.


### 3.2. Modifying the Program

The program you've completed is interactive in that it prompts the 
user for input.  You will now change the program to instead use *command 
line arguments* to read in the list of numbers directly from the command 
line.

Command line arguments are available to your main method through 
the `args` array of Strings.  The size of this array 
can be obtained by using `args.length` which is an
integer.  Modify your code to iterate through this array and convert 
the arguments to integers using the following snippet of code:

```java
for(int i=0; i<args.length; i++) {
  array[i] = Integer.parseInt(args[i]);
}
```

The *command line* may not be apparent as you are using an IDE.  
However, it is still available to you.  Instead of clicking the "Play" 
button to run your program, click the down arrow right next to it.  
Then select "Run Configurations".  This brings up a dialog box with 
which you can run custom configurations.  Click the Arguments tab and 
enter a space-delimited list of numbers under "Program Arguments"
and click "Run".


## 5. Testing and Submitting Your Lab

### 5.1 Testing

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

### 5.2 Submitting

Nearly all of your labs and projects will require you to hand in source files
for graders to compile and evaluate.  To do this, we use a web-based
assessment app called codepost.io (<https://codepost.io>).  

You should have received an invitation to this website from your
instructor through your email account (typically your `@huskers.unl.edu`
email or whatever email you have associated with on Canvas).  If
you have access, great.  If not, go to <https://codepost.io/forgot-password>
and "reset" your password (even if you never initially set one).  Be
sure to use your huskers email or whatever primary email is associated
with your canvas profile.

To handin and grade your lab, do the following.

1. Login to <https://codepost.io>.  It should immediately take you to the
   assignment submission page:
<p align="center">
<img src="images/codepost01-assignments-Xu.png" alt="Codepost.io Assignments" width="50%"/>
</p>

2. Click "Upload Assignment" which will bring up a dialog box.
<p align="center">
<img src="images/codepost02-submission-Xu.png" alt="Codepost.io Submission" width="50%"/>
</p>

3. Click "Upload files" to upload the following two required files located in your Eclipse workspace. Then click the "Submit and run test" button.

* `Statistics.java`: You do not need to make any changes to this file, as this lab just shows you how CodePost works.
* `Birthday.java`: Please change variable names with underscores to the preferred lowerCamelCasing convention in Java.

4. You should see something like the following:
<p align="center">
<img src="images/codepost04-success-Xu.png" alt="Codepost.io Success" width="50%"/>
</p>

***HOWEVER*** this does not mean that your program(s) worked, only that
they were uploaded.  You ***still need to view the results!!!***

5. Click on the "View test results" button to
view the test results which will give you more details.  If any
test(s) failed, you should see something like the following. You can click on the + button to see more details.  
<p align="center">
<img src="images/codepost07-failResults-Xu.png" alt="Codepost.io Fail View" width="60%"/>
</p>


If all tests passed, you should see something like this:
<p align="center">
<img src="images/codepost06-successResults-Xu.png" alt="Codepost.io Success View" width="60%"/>
</p>

Some things to understand about the lab grading process:

 * For this lab, as long as you pass all the tests, you will get full credit for the lab.
 * Some future labs may be manually examined by LAs to award or deduct additional points according to the specific lab requirements.
 * If there are problems or errors with your program(s),
   you should fix them and repeat the submission process.
	 You can do this as many times as you like up until the due date.  
 * In any case, it is **your responsibility to read, understand
   and *address* any and all errors and/or warnings that CodePost
   produces**.

***Congratulations on your first lab!***


