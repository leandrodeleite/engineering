
---
### Modular Programming with Python

---
04 __ Using Modules for Real-World Programming
```
Introducing Charter
Designing Charter
Implementing Charter
    Implementing the chart.py module
    Implementing the generator.py module
        The Pillow library
        Renderers
        Testing the code
        Rendering the title
        Rendering the x axis
        The remaining renderers
        Testing Charter
The fly in the ointment – changing requirements
Redesigning Charter
    Refactoring the code
    Implementing the PDF renderer modules
Testing the code
Lessons learned
Summary
```

---
*Preface, What this book covers*

Chapter 4, Using Modules for Real-World Programming, uses the implementation of a
chart-generation library to show how modular techniques help to deal with changing
requirements in the best possible way.

---
*Summary*


In this chapter,  
we used modular programming techniques  
to implement a hypothetical chart-generation package called Charter.  
We saw how charts are made up of standard elements, and  
how this organization can be translated into program code.  
After successfully creating a working chart-generation library  
that renders charts as bitmapped images,  
we saw how a fundamental change in requirements  
can seem to be a problem at first, but is actually  
an opportunity to refactor and improve your code.  

Following through with this hypothetical example,  
we refactored the Charter library to handle PDF formatted charts.  
In doing so, we learned that using modular techniques  
to respond to a major change in requirements can help  
to isolate the changes that need to be made, and  
that refactoring our code often results  
in a system that is better organized,  
more expandable and more robust than what we started with.  

In the next chapter,  
we will learn how to use standard modular programming "patterns"  
to deal with a range of programming challenges.  

---
*Intro*

In this chapter,  
we are going to use modular programming techniques  
to implement a useful real-world system.  
In particular, we will:  

- Design and implement a Python package for generating charts  
- See how changing requirements can be the downfall of a successful system  
- Discover the ways in which modular programming techniques can help you
to deal with changing requirements in the best possible way  
- Learn that changing requirements can be good, because they give you
the opportunity to re-think your program, resulting in more robust and
well-designed code  

Let's start by looking  
at the Python chart-generating package we are going to implement,  
which we will call Charter.  

