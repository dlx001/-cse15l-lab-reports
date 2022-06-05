# Lab Report 5 #

This lab was performed by comparing the two markdownparser files: our own and the provided one by the instructors. After running the script.sh that ran many tests on both parsers and sending that data to a file called results.txt, it was then vimdiffed. 

At this point, our screen looked like this

![image](Vimdiff.PNG)

After looking through the tests, it was noted that test 481 had different output 

![image](Wrong.PNG)

The markdown for 481.md is 

` [link](/uri "title") ` 

based on markdown preview, the expected output is /uri "title which our implementation got correct and the provided didn't. 

Looking at the provided markdownparser