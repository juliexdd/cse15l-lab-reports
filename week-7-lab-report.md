#### Week 7 Lab Report - Julie Nguyen
# Lab Report 4 - CLDQ – CSE Labs “Done Quick”

## CLDQ – CSE Labs “Done Quick”: Reproducing Tasks from Competition

### 1. Log into ieng6
![Image](https://cdn.discordapp.com/attachments/793015871979257896/1079748740551803011/Screen_Shot_2023-02-27_at_4.55.37_AM.png)
- Keys pressed: *`<Command-C><Command-V><enter>`*
- I have my ssh login for ieng6 saved on a separate tab on my computer, so I simply copied the command using `<Command-C>` and pasted it into the terminal using `Command-V`. Then, I hit `<enter>` to run the command and was able to successfully login.

### 2. Clone your fork of the repository from your Github account
![Image](https://cdn.discordapp.com/attachments/793015871979257896/1079751667563643060/Screen_Shot_2023-02-27_at_5.07.31_AM.png)
- Keys pressed: typed `git clone`,*`<Command-C><Command-V><enter>`*
- `git clone` is the command used to clone a repository. Then, I simply copied the ssh link from the repository from my Github account using `<Command-C>` and pasted it into the terminal using `<Command-V>`. Then , I hit `<enter>` to run the command and was able to successfully clone my fork of the repository from my Github account.

### 3. Run the tests, demonstrating that they fail
![Image](https://cdn.discordapp.com/attachments/793015871979257896/1079754242413309953/Screen_Shot_2023-02-27_at_5.17.46_AM.png)
- Keys pressed: typed `cd l` + *`<tab>`* + *`<enter>`*, *`<Command-C><Command-V><enter>`*, *`<Command-C><Command-V>`* typed `T` + *`<tab>`* + *`<enter>`*
- You have to change directories into the `lab 7` directory first. Then, I simply copied the `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java` command line (saved on a separate tab on my computer) by using `<Command-C>`. I hit `<enter>` to run the compile command. Then, I pasted the `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore TestListExamples` command line (also saved on a separate tab on my computer) using `<Command-V>`. Then, I typed `T` and hit `<tab>` because it will autofill the rest of the `TestListExamples` name. Finally, I hit `<enter>` to run the command and was able to successfully run the tests to showed that they fail.

### 4. Edit the code file to fix the failing test
- PERVIOUS CODE
![Image](https://cdn.discordapp.com/attachments/1024753720187179009/1079994614544601198/Screen_Shot_2023-02-27_at_9.12.57_PM.png)
- FIXED CODE
![Image](https://cdn.discordapp.com/attachments/1024753720187179009/1079994791837843466/Screen_Shot_2023-02-27_at_9.13.39_PM.png)
- Keys pressed: typed `nano` + `L` + *`<tab>`* + *`<enter>`*, scrolled with trackpad/mouse and changed the code's `index1` to `index2`, *`<Ctrl-O>`* + *`<Ctrl-M-A>`* + *`<Ctrl-X>`*
- `nano` allows you to edit a file within the terminal. The use of *`<tab>`* allowed it to automatically fill in the rest after typing `L` to speed things up instead of typing the entire file name. I found that scrolling through the file's code is faster than holding down the *`<down>`* arrow key. *`<Ctrl-O>`* allows you to save the changes you made to the file's code. *`<Ctrl-M-A>`* appends while *`<Ctrl-X>`* allows you to exit the nano terminal screen.

### 5. Run the tests, demonstrating that they now succeed
![Image](https://cdn.discordapp.com/attachments/1024753720187179009/1079995221464600649/Screen_Shot_2023-02-27_at_9.15.20_PM.png)
- Keys pressed: *`<up><up><up><enter>`*, *`<up><up><up><enter>`*
- The `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java` command was 3 up in my search history, so I used the `<up>` arrow key to access it. I hit `<enter>` to run the compile command. Then, the `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore TestListExamples` command was 3 up in my search history, so I used `<up>` to accessed it the same way. Finally, I hit `<enter>` to run the command and was able to successfully run the tests.

### 6. Commit and push the resulting change to your Github account
![Image](https://cdn.discordapp.com/attachments/793015871979257896/1079993205648543804/Screen_Shot_2023-02-27_at_9.07.17_PM.png)
- Keys pressed: typed `git commit L` + *`<tab>`* typed `-m "edited"` + *`<enter>`*, typed `git push` + *`<enter>`*
- `git commit` is a command that allows you to commit to Github. I pressed `<tab>` after the `L` because it will autofill the rest of the name. `-m "edited"` is used to write a message about your changes; I chose to write `"edited"` for example. Then, I pressed `<enter>` to run the command line. Next, I typed `git push` because this command will allow you to push the resulting change onto the Github account. Finally, I pressed `<enter>` to run the command and was able to successfully Commit and push the resulting change to the Github account.
