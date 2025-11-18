
---
### Modular Programming with Python

---
06 __ Creating Reusable Modules
```
Using modules and packages to share your code
What makes a module reusable?
    Functioning as a standalone unit
    Using relative imports
    Noting external dependencies
What makes a good reusable module?
    Solving a general problem
    Following standard conventions
    Having clear documentation
Examples of reusable modules
    requests
    python-dateutil
    lxml
Designing a reusable package
Implementing a reusable package
Testing our reusable package
Summary
```

---
*Preface, What this book covers*

Chapter 6, Creating Reusable Modules, shows how to design and create modules and
packages that are intended to be shared with other people.

---
*Summary*

In this chapter,  
we looked at the concept of a reusable module or package.  
We saw how reusable packages and modules can be used  
to share code with other people.  
We learned that a reusable module or package  
needs to function as a standalone unit,  
should ideally use relative imports, and  
should note any external dependencies it may have.  
Ideally,  
a reusable package or module will also solve a general problem  
rather than a specific one, follow standard Python coding conventions, and  
have good documentation.  
We then looked at some examples of good reusable modules,  
before writing one of our own.  

In the next chapter,  
we will look at some of the more advanced aspects  
of working with modules and packages in Python.  

---
*Intro*

As well as being a good technique for writing programs for your own use,  
modular programming is also an excellent way of writing programs  
that can be used by other programmers.  
In this chapter,  
we will look at how to design and implement modules and packages  
that can be shared and reused in other programs.  

In particular, we will:  
- See how modules and packages can be used as a way of sharing the code that
you write  
- See how writing a module for reuse differs from writing a module for use as
part of just one program  
- Discover what makes a module suitable for reuse  
- Look at examples of successful reusable modules  
- Design a package to be reusable  
- Implement a reusable package  

Let's start by taking a look at how you can use modules and packages  
to share your code with other people.  

