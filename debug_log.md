# Debug Log

**Explain how you used the VSCode debugger tools to uncover the bugs in Exercise 7. Be specific. What breakpoints did you set? Where did you step to? What made you realize the error?**

_Example: I set a breakpoint on line 5 and stepped until line 12. There, I discovered that the `x` variable had a value of `-3`, whereas it should have had a value of `7`. That made me realize that we should be adding the two numbers `x` and `y`, instead of subtracting._


For Exercise 5: I set a break point on line 11 and stepped until line 12. At that point, I was getting an index out range error. I switched the range from (0, len(list_of_nums)) to (1, len(list_of_nums)) and i, i+1 to i-1, i to avoid index out of range error. 


For Exercise 7: I set a break point on line 10 where I realized I got the variable wrong when accessing substring for remaning words. I stepped until 13 where I noticed the same error on the substring. I changed start_str to sentence on both lines. 

