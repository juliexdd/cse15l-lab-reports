### Week 1 Lab Report
# How to Log into a Course-Specific Account on ieng6

## Installing VScode

1. Go to the [VScode](https://code.visualstudio.com/) website.
2. Click on the button that says "Download".
![Image](https://cdn.discordapp.com/attachments/793015871979257896/1064506929398951976/Screen_Shot_2023-01-16_at_3.30.22_AM.png)
3. Choose the download option that is compatible with your device's operating system.
![Image](https://cdn.discordapp.com/attachments/793015871979257896/1064508947807076362/Screen_Shot_2023-01-16_at_3.38.25_AM.png)
4. Install VScode.

## Remotely Connecting

1. Because my device's operating system is MacOS, I did not need to install [Git for Windows](https://gitforwindows.org/).
2. Open up a new blank file on VScode and open a new terminal by going to terminal -> new terminal.
![Image](https://cdn.discordapp.com/attachments/793015871979257896/1064619916969377884/Screen_Shot_2023-01-16_at_10.59.22_AM.png)
3. Type in "ssh cs15lwi23zz@ieng6.ucsd.edu" without the quotation marks and replace "zz" with your unique letters in your course-specific account.
> ssh cs15lwi23zz@ieng6.ucsd.edu
4. Here, it will prompt you to type in your password.
5. It will look like this when you successfully login.
![Image](https://cdn.discordapp.com/attachments/793015871979257896/1063720728295383150/Screen_Shot_2023-01-13_at_11.26.19_PM.png)

## Trying Some Commands

1. If you type "ls -lat" without the quotation marks in the terminal, it will create a list of files sorted by modification time from the connected remote computer.
> ls -lat
![Image](https://cdn.discordapp.com/attachments/793015871979257896/1064693444343255090/Screen_Shot_2023-01-16_at_3.51.30_PM.png)
2. If you type "ls -a" without the quotation marks in the terminal, it will create a list of all the files not in a long list format from the connected remote computer.
> ls -a
![Image](https://cdn.discordapp.com/attachments/793015871979257896/1064694976837074984/Screen_Shot_2023-01-16_at_3.57.36_PM.png)
3. If you use the "cd" command, it will allow you to change the directory, hence the long name "change directory".
4. If you type "cat /home/linux/ieng6/cs15lwi23/public/hello.txt", it will open up and read the file named hello.txt.
> cat /home/linux/ieng6/cs15lwi23/public/hello.txt
![Image](https://cdn.discordapp.com/attachments/793015871979257896/1064699559999176814/Screen_Shot_2023-01-16_at_4.15.48_PM.png)
5. There are many more commands, but these are some of the basic useful ones for now!
