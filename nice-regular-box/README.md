# Nice Regular Box

Write a program **NiceRegularBox.kt**. 

Your program will read in a number (no need to prompt the user), and then reads in that number of lines from the terminal.  Then the program should print an list of strings formatted in a nice regular box.

So if the user inputs this:
```
5
Grim visaged war has smooth’d his wrinkled front
And now, instead of mounting barded steeds
To fright the souls of fearful adversaries
He capers nimbly in a lady’s chamber
To the lascivious pleasing of a lute
 ```

The program should print:
```
++++++++++++++++++++++++++++++++++++++++++++++++++++
+ Grim visaged war has smooth’d his wrinkled front +
+ And now, instead of mounting barded steeds       +
+ To fright the souls of fearful adversaries       +
+ He capers nimbly in a lady’s chamber             +
+ To the lascivious pleasing of a lute             +
++++++++++++++++++++++++++++++++++++++++++++++++++++
 ```
 
# Files in this repo
The files in this repo contain:
- README.md: this file
- Dockerfile: this is used for the autograder to grade your work. It uses docker, which is outside the scope of the course, but you're welcome to learn more at docker.com.
- tests: the input and expected outputs for testing your program is here.

Put your NiceRegularBox.kt in the root directory of this repo, next to README.md and Dockerfile.

# Testing
The homework includes an automated script that checks your program against a set of inputs and the expected output.
You can see the files in the test directory.

On a Unix system, run the test script with
```
/path/to/tests/TestRunner.sh /path/to/NiceRegularBox.kt
```

So for example, if your NiceRegularBox.kt is in the same directory as this README.md, and you're in the same working 
directory as your kt file, then run
```
tests/TestRunner.sh NiceRegularBox.kt
```

If everything works, the test script will respond with
```
Test Case 1... Success
Test Case 2... Success
Test Case 3... Success
Test Case 4... Success
Test Case 5... Success
Total points=10
```

# Submitting
Submit your **NiceRegularBox.kt** file.

# Autograding
The autograder will run against your submission and check your output against the expected output. 
