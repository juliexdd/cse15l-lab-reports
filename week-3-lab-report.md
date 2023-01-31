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
- The value of String variable is modified with each search as the next set of word(s) is concatenated to the String in storage/memory. The String parameter at index [1] is also changed depending on what word(s) were typed.
3. Seconds screenshot of using `/add-message` with the text `was here ! :)`.
![Image](https://cdn.discordapp.com/attachments/793015871979257896/1069794236989444136/Screen_Shot_2023-01-30_at_5.40.17_PM.png)
- The method called on is `public String handleRequest`. Inside here, the method will check if the URL contains `/`, and it will return that set as a new string. Next, the method will get the path of the url and check if it contains `/add-message`. If it does, then the method will grab and assign the String's parameters before and after the split at `=`. Next, the method will check if the parameter at index [0] contains `s`. If it does, then the method will concatenate the String in parameter at index [1] to the string in storage/memory.
- The relevant arguments are String variable, string parameters [0] and [1], and URI url. The value of the String variable is, at first, an empty string `""`; however, when `/add-message` is used, whatever string of text is used after the `=` is concatenated to the string in storage/memory. In this context, the string of text concatenated to the initial empty string is `was here ! :)`, which is also the value of String parameter [1].
- The value of String variable is modified with each search as the next set of word(s) is concatenated to the String in storage/memory. The String parameter at index [1] is also changed depending on what word(s) were typed.

## Part 2 - Bugs

1. The bug I chose from Lab 3 is the `averageWithoutLowest`.
2. A failure-inducing input was `{ 3, 3, 3, 3}`. The expected output should be 3.0, but the actual output ended up being 0.0, which is wrong.
```
double[] input1 = { 3,3,3,3 };
assertEquals(3.0, ArrayExamples.averageWithoutLowest(input1), 0.1);
```
3. An input that does not induce a failure is `{ 2, 3, 4, 5 }`. The expected output is 4.0, and the actual output is 4.0, which is correct.
```
double[] input1 = { 2,3,4,5 };
assertEquals(4.0, ArrayExamples.averageWithoutLowest(input1), 0.1);
```
4. The symptom is that if there is more than one exact same lowest number, then `averageWithoutLowest` will delete all of the duplicated lowest number.
- This is a failure-inducing input.
![Image](https://cdn.discordapp.com/attachments/793015871979257896/1069832468024271020/Screen_Shot_2023-01-30_at_8.12.12_PM.png)
- This is an input that does not induce a failure.
![Image](https://cdn.discordapp.com/attachments/793015871979257896/1069838930125537350/Screen_Shot_2023-01-30_at_8.37.50_PM.png)
5. The bug before the code change fix.
```
static double averageWithoutLowest(double[] arr) {
    if(arr.length < 2) { return 0.0; }
    double lowest = arr[0];
    for(double num: arr) {
      if(num < lowest) { lowest = num; }
    }
    double sum = 0;
    for(double num: arr) {
      if(num != lowest) { sum += num; }
    }
    return sum / (arr.length - 1);
  }
```
7. The bug after the code change fix. The fix addresses the issue because the `counter` variable prevents duplicate lowest numbers from being removed from the array, and it ensures that only one lowest number is removed when doing the calculation.
```
static double averageWithoutLowest(double[] arr) {
    if(arr.length < 2) { return 0.0; }
    double lowest = arr[0];
    for(double num: arr) {
      if(num < lowest) { 
        lowest = num; 
      }
    }
    double sum = 0;
    int counter = 0;
    for(double num: arr) {
      if(num == lowest && counter == 0 ) {
        counter++;
        continue;
      }
      else {
        sum += num; 
      }
    }
    return (double)(sum / (arr.length - 1));
  }
```

## Part 3 - Something You Learned From Lab In Week 2 or Week 3
1. Something I learned from lab was how to create a web server. This was interesting to make because I never thought that a server would be easy to make! Visiting other people's servers was fascinating to think about the logic behind it, and how we were able to modify or add to each other's servers.
