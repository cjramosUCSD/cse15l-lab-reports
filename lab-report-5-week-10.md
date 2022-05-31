# Week 10 Lab Report
### Chester James Ramos 
# [Reposititory](https://cjramosucsd.github.io/cse15l-lab-reports/)

## **How I found my test**
I found my test through running a print statement on the given implementation in week 9 to show all the link list. Heres a picture of the code i ran and the output. 
![Image](testlist.jpg)
From there I manual tested randoms ones and compared the outputs on my own implementation by just adding the file and creating a test in 
MarkdownParseTest.
## **Test 1**
For this one I choose test file 495:
[Link for test file 495](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/495.md)

My output: (Ignore the comparison) <br> 
![image](output2.jpg)

Given repository output: <br>
![image](output1.jpg)

The correct one is the given repository output as shown in commonmark
![image](common1.jpg)
and the given link or output will be next to href in the image below
![image](common2.jpg) 

### **Problem/Fix**
![Image](problem1.jpg)
The problem that has to fixed here is the checking of parentheses. As shown here the code is only checking for the first sighting of a openign parentheses and the first sighting of a closing parentheses. So to fix this it should look for the first sighting of an opening parentheses and the last sighting of a closing parentheses.

## **Test 2**
For this one I choose test file 519:
[Link for test file](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/519.md)

My output: <br>
![image](output4.jpg)
Given repository output: <br>
![image](output3.jpg)

The correct one is my repository output as shown in commonmark
![image](common3.jpg)
Since there is no href there should be no links as shown below
![image](common4.jpg)

### **Problem/Fix**
![image](problem2.jpg)
The problem here is that it the implementation doesn't check for exclaimation marks before the open bracket. As shown here it just looks for the open brackets and moves forward from there instead of checking the letter before the opening bracket. To fix this just create an if statement to check after it finds an open bracket if the character before it is an exclaimation point. 


