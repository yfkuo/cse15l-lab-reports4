# Lab Report 4 - Vim (Week 7)

- This was what the fork looked like before I committed the changes to my Github account:

![Image](originfork.png)


## 4. Log into ieng6:
- First, key press `<up>` arrow for 2 times to find `ssh cs15lfa23nn@ieng6.ucsd.edu` command from the history, then press `<enter>`:

![Image](step4.png)


## 5. Clone your fork of the repository from your Github account (using the SSH URL):
- After the previous step, key press `<up>` arrow for 8 times to find SSH URL `git@github.com:yfkuo/lab7.git` command from the history, then press `<enter>`:

![Image](step5.png)


## 6. Run the tests, demonstrating that they fail:
- Next, key press `<down>` arrow for 1 times to find `cd lab7` command from the history, then press `<enter>` to change current working directory to `lab7`.
- Next, then key press `<down>` arrow for 1 times to find `bash test.sh` command from the history, then press `<enter>` to run the tests.
- Image demonstrates the tests failures:

![Image](step6.png)


## 7. Edit the code file to fix the failing test:

- Next, key press `<down>` arrow for 1 times to find `vim ListExamples.java` command from the history, then press `<enter>` to edit `ListExamples.java`.

![Image](step7.1.png)


- Next, to find `index1` in `ListExamples.java`: Type `/index1`, then press `<enter>` to select the first found `/index1` in the java file.

![Image](step7.2.png)


- Next, press `<n>` for 9 times to get to the desired `index1` that we want to change to `index2`.
- Note that the lower right corner will show the number of the line that you are currently at, which is line 44.

![Image](step7.3.png)


- Next, type `:44s/index1/index2` to select `index1` on line 44.

![Image](step7.4.png)


- Next, press `<enter>` after typing `:44s/index1/index2` to change `index1` on line 44 to `index2`.

![Image](step7.5.png)


- Next, to save the changes and quit from `vim ListExamples.java`, type `:wq!` then press `<enter>`.

![Image](step7.6.png)


## 8. Run the tests, demonstrating that they now succeed:
- Next, key press `<down>` arrow for 1 times to find `bash test.sh` command from the history, then press `<enter>` to run the tests again.

![Image](step8.png)


## 9. Commit and push the resulting change to your Github account, type in the following commands:
- Next, key press `<down>` arrow for 1 times to find `git add ListExamples.java` command from the history, then press `<enter>` to add changes.
- Next, key press `<down>` arrow for 1 times to find `git commit -m "update ListExamples.java"` command from the history, then press `<enter>` to commit the changes.
- Next, key press `<down>` arrow for 1 times to find `git push origin main` command from the history, then press `<enter>` to push committed changes back to the repository I forked to my Github account.

![Image](step9.1.png)

- Now, this image demonstrate the change has sucessfully made to my Github account:

![Image](step9.2.png)


  
