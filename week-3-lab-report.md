#### Week 3 Lab Report - Julie Nguyen
# Lab Report 2 - Servers and Bugs

## Part 1 - Web Server

1. Web Server Script for `StringServer.java`.
![Image](https://cdn.discordapp.com/attachments/793015871979257896/1069794471132266526/Screen_Shot_2023-01-30_at_5.41.13_PM.png)
![Image](https://cdn.discordapp.com/attachments/793015871979257896/1069794572693164072/Screen_Shot_2023-01-30_at_5.41.37_PM.png)
![Image](https://cdn.discordapp.com/attachments/793015871979257896/1069794656835092520/Screen_Shot_2023-01-30_at_5.41.57_PM.png)
![Image](https://cdn.discordapp.com/attachments/793015871979257896/1069794750938492968/Screen_Shot_2023-01-30_at_5.42.19_PM.png)
2. First screenshot of using `/add-message` with the text `Julie Nguyen`.
![Image](https://cdn.discordapp.com/attachments/793015871979257896/1069794085059174451/Screen_Shot_2023-01-30_at_5.39.41_PM.png)
- The method called on is `public String handleRequest`. Inside here, the method will check if the URL contains `/`, and it will return that set as a new string. Next, the method will get the path of the url and check if it contains `/add-message`. If it does, then the method will grab and assign the String's parameters before and after the split at `=`. Next, the method will check if the parameter at index [0] contains `s`. If it does, then the method will concatenate the String in parameter at index [1] to the string in storage/memory.
- The relevant arguments are String variable, string parameters [0] and [1], and URI url. The value of the String variable is, at first, an empty string `""`; however, when `/add-message` is used, whatever string of text is used after the `=` is concatenated to the string in storage/memory. In this context, the string of text concatenated to the initial empty string is `Julie Nguyen`, which is also the value of String parameter [1].
3. Seconds screenshot of using `/add-message` with the text `was here ! :)`.
![Image](https://cdn.discordapp.com/attachments/793015871979257896/1069794236989444136/Screen_Shot_2023-01-30_at_5.40.17_PM.png)
