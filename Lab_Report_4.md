# Lab Report 4 - vim

`commands + <Enter>` means hit the enter key after typing the command.

### Step 4:Log into ieng6:

Keys pressed: Open up a new terminal and type the command `ssh cs15lfa23sa@ieng6-202.ucsd.edu + <Enter>`.

![image](https://raw.githubusercontent.com/zmc0806/cse15L-lab-report4/main/report5-1.jpeg)

First logged into ieng6 without password

### Step 5: Clone your fork of the repository from your GitHub account (using the SSH URL):

Key pressed: git clone the ssh URL of the provided GitHub repo by using `git clone git@github.com:zmc0806/lab7.git + <Enter>`.

![image](https://raw.githubusercontent.com/zmc0806/cse15L-lab-report4/main/report5-2.jpeg)

Then clone my fork of repository from github by using the SSH URL

### Step 6: Run the tests

Key pressed: type `cd lab7/ + <Enter>` into the lab7 file, then check the files by typing `ls + <Enter>`. Run the bash script by bash `test.sh + <Enter>`

The result is Tests run: 2,Failures: 1

![image](https://raw.githubusercontent.com/zmc0806/cse15L-lab-report4/main/report5-3.jpeg)



![image](https://raw.githubusercontent.com/zmc0806/cse15L-lab-report4/main/report5-4.jpeg)

Now we should edit ListExamples.java.Using command `vim ListExamples.java` to open the java file and then type i to insert and then type esc to quit,last use `:wq` to save and quit vim

![image](https://raw.githubusercontent.com/zmc0806/cse15L-lab-report4/main/report5-5.jpeg)

Running the test after editing,now it's all pass.

![image](https://raw.githubusercontent.com/zmc0806/cse15L-lab-report4/main/report5-6.jpeg)

Last git add and commit and last git push
