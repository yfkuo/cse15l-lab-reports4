# Lab Report 4 - Vim (Week 7)
1. Setup: Delete any existing forks of the repository you have on your account
2. Setup: Fork the repository
![Image](originfork.png)
3. The real deal: Start the timer!


## 4. Log into ieng6, type:

![Image](step4.png)


## 5. Clone your fork of the repository from your Github account (using the SSH URL), type:

![Image](step5.png)


## 6. Run the tests, demonstrating that they fail:

![Image](step6.png)


## 7. Edit the code file to fix the failing test:

- Type `vim ListExamples.java` to edit `ListExamples.java`.

![Image](step7.1.png)


- To find `index1` in `ListExamples.java`: Press `</index1>` `<enter>`.

![Image](step7.2.png)


- Press `<n>` for 9 times to get to the `index1` that we want to change to `index2`.

![Image](step7.3.png)


- Then type `<:44s/index1/index2>` to select `index1` on line 44.

![Image](step7.4.png)


- Then press `<enter>` after typing `<:44s/index1/index2>` to change `index1` on line 44 to `index2`.

![Image](step7.5.png)


- To save the changes, type `<:wq!>` then press `<enter>`.

![Image](step7.6.png)


## 8. Run the tests, demonstrating that they now succeed:

![Image](step8.png)


## 9. Commit and push the resulting change to your Github account, type in the following commands:

![Image](step9.1.png)

![Image](step9.2.png)


  
