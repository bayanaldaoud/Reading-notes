# **<span style="color:#d85164">Error Handling & Debugging </span>**

![](https://miro.medium.com/max/1200/1*EAlxWCsiV4x39VjYRzhOUw.png)


Sometimes a code may contain certain mistakes. Being a scripting language, JavaScript didn't show any error message in a browser. But these mistakes can affect the output.

The best practice to find out the error is to debug the code. The code can be debugged easily by using web browsers .

To perform debugging, we can use any of the following approaches:
##  Using console.log() method

The **console.log()** method displays the result in the console of the browser. If there is any mistake in the code, it generates the error message.
## Using debugger keyword

In debugging, generally we set breakpoints to examine each line of code step by step. There is no requirement to perform this task manually in JavaScript.

JavaScript provides debugger keyword to set the breakpoint through the code itself. The debugger stops the execution of the program at the position it is applied. Now, we can start the flow of execution manually. If an exception occurs, the execution will stop again on that particular line.

![](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/08/JavaScript-Debugging-and-Testing.png)