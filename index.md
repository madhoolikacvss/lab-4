# Lab report 4 

1. Setup Delete any existing forks of the repository you have on your account
   As I initially forked this repository in the lab, I had to delete it. For that I did the following: 
    * Opened VSCode
    * Input the command `ssh cs15lwi23ajz@ieng6.ucsd.edu` into the terminal
    * Went ahead and typed in my password
    * I then typed in the command `rm -rf lab7` in the command line to delete the existing cloned repository
    ![deleting old repo](https://user-images.githubusercontent.com/122486374/221492937-2e459c06-8d95-4e39-8e11-da71e4a49dc4.jpg)

2. Clone your fork of the repository from your Github account
   Now, to clone the repository, I went onto the class website to copy the url of the repository. Then I did `git clone + right click(pasts the url down)` 
   ![git clone ](https://user-images.githubusercontent.com/122486374/221513262-c5b0ba87-9d1f-42b3-98d8-a6567923d329.jpg)


3. Run the tests, demonstrating that they fail
   * I first cd-ed into lab7 byt typing th following `cd l<tab>`
   * Then I went to the week 3's course website to copy down the command to compile all files and run them 
   * To copy it into the terminal, I right clicked
   * The command copied is `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java`
   * The command to run the tests is `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore T<tab>j<tab>`
   ![test fail](https://user-images.githubusercontent.com/122486374/221513329-afd1ff10-8f4d-423a-8e63-991cebe17f2b.jpg)


4. Edit the code file to fix the failing test
   To fix the filter method, I did the following:
   * `nano L<tab>j<tab>`
   * `ctrl + w add(`
   * `<right><right><right><right>`
   * backspace
   * Typed in `result.size()`
   To fix the merge method I did the following:
   * `ctrl + w index1`
   * `<down><down><down><down><down><down><right><right><backspace>`
   * typed in 2 - this changed the variable being incremented from index1 to index2
   ![fixed code](https://user-images.githubusercontent.com/122486374/221513384-c798a9ae-e74c-4756-8d95-8450d20aa18f.jpg)

   To save and exit I did the following:
   * `ctrl + o <enter> ctrl + w`
   
5. Run the tests, demonstrating that they now succeed
   * As I had already run the command for this before, I just did `<up><up>`
   
6. Commit and push the resulting change to your Github account (you can pick any commit message!)
   * `git add L<tab>j<tab>`
   * `git add T<tab>j<tab>`
   * `git commit -m "Updated versions"`
   ![commit](https://user-images.githubusercontent.com/122486374/221515215-b8e22cd2-52d3-416d-a7b7-d8620f8d66c9.jpg)

   
