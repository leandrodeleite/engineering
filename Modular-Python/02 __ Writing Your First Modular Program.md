
---
### Modular Programming with Python

---
02 __ Writing Your First Modular Program
```
The inventory control system
Designing the inventory control system
    The data storage module
    The user interface module
    The report generator module
    The main program
Implementing the inventory control system
    Implementing the data storage module
    Implementing the user interface module
    Implementing the report generator module
    Implementing the main program
Summary
```

---
*Preface, What this book covers*

Chapter 2, Writing Your First Modular Program, introduces the divide and conquer
approach to programming and applies this technique to the process of building an
inventory control system based on modular programming principles. 

---
*Summary*

In this chapter,  
we designed and implemented a non-trivial program  
to keep track of a company's inventory.  
Using the divide-and-conquer approach,  
we split the program into individual modules and then  
looked at the functionality that each module would need to provide.  
This led us to  
a more detailed design of the functions within each module, and  
we were then able to implement the overall system one step at a time.  
We discovered that  
some functionality had been overlooked and  
had to be added after the design was complete, and saw  
how modular programming makes it less likely  
for these types of changes to break your system.  
Finally,  
we had a quick play with the inventory control system to make sure it works.  

In the next chapter,  
we will learn more about the nuts and bolts of  
how modules and packages work within Python.  

---
*Intro*

In this chapter,  
we will use modular programming techniques  
to implement a non-trivial program.  
Along the way, we will:  

_ Learn about the divide and conquer approach to program design  
_ Examine the tasks our program needs to perform  
_ Look at the information our program will need to store  
_ Apply modular techniques to break our program down into individual parts  
_ Figure out how each part can be implemented as a separate Python module  
_ See how the various modules work together to implement our program's
functionality  
_ Follow this process to implement a simple but complete  
inventory control system  
_ See how modular techniques allow you to add functionality to your program  
while minimizing the changes that need to be made  

