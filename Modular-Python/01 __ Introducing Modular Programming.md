
---
### Modular Programming with Python

---
01 __ Introducing Modular Programming
```
Introducing Python modules
Introducing Python packages
Using modules and packages to organize a program
Why use modular programming techniques?
Programming as a process
The Python Standard Library
Creating your first module
    Caching
    Writing a cache module
    Using the cache
Summary
```

---
*Preface, What this book covers*

Chapter 1, Introducing Modular Programming, looks at the ways you can use Python
modules and packages to help organize your programs, why it is important to use
modular techniques, and how modular programming helps you to deal with the
ongoing process of programming.

---
*Summary*

In this chapter,  
we introduced the concept of Python modules and  
saw how Python modules are simply Python source files,  
which are imported and used by another source file.  
We then took a look at Python packages and  
saw that these are collections of modules identified  
by a package initialization file named `__init__.py`. 

We explored  
how modules and packages can be used  
to organize your program's source code and  
why the use of these modular techniques is so important  
for the development of large systems.  
We also explored what spaghetti code looks like and  
discovered some of the other pitfalls that can occur  
if you don't modularize your programs.

Next, we looked at  
programming as a process of constant change and evolution and  
how modular programming can help deal with a changing codebase  
in the best possible way.  
We then learned that  
the Python Standard Library is an excellent example of  
a large collection of modules and packages, and  
finished by creating our own simple Python module  
that demonstrates effective modular programming techniques.  
In implementing this module,  
we learned how a module can use leading underscores  
in variable and function names to mark them as private to the module,  
while making the remaining functions and other definitions  
available for other parts of the system to use.

In the next chapter,  
we will apply modular techniques to the development  
of a more sophisticated program consisting of several modules working together  
to solve a more complex programming problem.

---
*Intro*

Modular programming is an essential tool for the modern developer.  
Gone are the days when you could just throw something together and hope that it works.  
To build robust systems that last,  
you need to understand how to organize your programs  
so that they can grow and evolve over time.  
Spaghetti coding is not an option.  
Modular programming techniques,  
and in particular the use of Python modules and packages,  
will give you the tools you need to succeed as a professional  
in the fast changing programming landscape.

In this chapter, we will:
_ Look at the fundamental aspects of modular programming  
_ See how Python modules and packages can be used to organize your code  
_ Discover what happens when modular programming techniques are not used  
_ Learn how modular programming helps you stay on top of the
development process  
_ Take a look at the Python standard library as an example of modular
programming  
_ Create a simple program, built using modular techniques, to see how it
works in practice  

Let's get started by learning about modules and how they work.

